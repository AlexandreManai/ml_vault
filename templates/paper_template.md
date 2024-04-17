---
publish: 
aliases:
  - "{{title}}"
  - "@{{citekey}}"
tags:
  - research
authors: "{{authors}}"
year: '{{date | format ("YYYY")}}'
---
<%*
	let title = "{{title}}";
	let date = tp.date.now("YYYY-MM-DD");
	await tp.file.rename(`${date} - ${title}`)
%>

> [!Link]-
> zotero_link:: {{pdfZoteroLink}}

> [!Abstract]-
> abstract:: {{abstractNote}}

> [!Related]-
> related:: {{related}}

{% for annotation in annotations -%}
	{%- if annotation.annotatedText -%}
		- "{{annotation.annotatedText | escape}}"{% if annotation.color %} | <mark style="background: {{annotation.color}}">{{annotation.type | capitalize}}</mark>  {% else %} {{annotation.type | capitalize}} {% endif%} ([{{annotation.page}}](zotero://open-pdf/library/items/{{annotation.attachment.itemKey}}?page={{annotation.page}}&annotation={{annotation.id}}))
	{%- endif %}
	{%- if annotation.imageRelativePath -%}
		![[{{annotation.imageRelativePath}}]]
	{%- endif %}
	{% if annotation.comment %}
		- {{annotation.comment}}
	{% endif %}
{% endfor -%}
