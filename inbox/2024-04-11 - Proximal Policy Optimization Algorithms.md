---
publish: true
aliases:
  - Proximal Policy Optimization Algorithms
  - "@schulmanProximalPolicyOptimization2017"
tags:
  - research
authors: John Schulman, Filip Wolski, Prafulla Dhariwal, Alec Radford, Oleg Klimov
year: "2017"
---


> [!Link]-
> zotero_link:: [Full Text](zotero://select/library/items/BTZRZZ8W)

> [!Abstract]-
> abstract:: We propose a new family of policy gradient methods for reinforcement learning, which alternate between sampling data through interaction with the environment, and optimizing a "surrogate" objective function using stochastic gradient ascent. Whereas standard policy gradient methods perform one gradient update per data sample, we propose a novel objective function that enables multiple epochs of minibatch updates. The new methods, which we call proximal policy optimization (PPO), have some of the benefits of trust region policy optimization (TRPO), but they are much simpler to implement, more general, and have better sample complexity (empirically). Our experiments test PPO on a collection of benchmark tasks, including simulated robotic locomotion and Atari game playing, and we show that PPO outperforms other online policy gradient methods, and overall strikes a favorable balance between sample complexity, simplicity, and wall-time.

> [!Related]-
> related:: 

- "proximal policy optimization" | <mark style="background: #5fb236">Highlight</mark>   ([1](zotero://open-pdf/library/items/BTZRZZ8W?page=1&annotation=F2FCKK66))
	
		- interesting
	
- "several different approaches" | <mark style="background: #ffd400">Highlight</mark>   ([1](zotero://open-pdf/library/items/BTZRZZ8W?page=1&annotation=E3MWNNHZ))
	
		- Not hat Importanz '
	
- "leading contenders" | <mark style="background: #a28ae5">Highlight</mark>   ([1](zotero://open-pdf/library/items/BTZRZZ8W?page=1&annotation=RDL8IFGM))
	
		- yeah
	
- "tood, vanilla policy gradient methods have poor data effiency and robustness; and trust region policy optimization (" | <mark style="background: #2ea8e5">Highlight</mark>   ([1](zotero://open-pdf/library/items/BTZRZZ8W?page=1&annotation=YER6JSQQ))
	
		- blue
	
- "y and reliable performance of TRPO, while using only first-order optimization. We propose a novel objective with clipped probability ratios, which forms a pessimistic estimate (i.e., lower bound) of the performance of the poli" | <mark style="background: #a28ae5">Highlight</mark>   ([1](zotero://open-pdf/library/items/BTZRZZ8W?page=1&annotation=M94ARYYA))
	
- "d that the version with the clipped probability ratios performs best. We also compare PPO to several previous algorithms from the li" | <mark style="background: #5fb236">Highlight</mark>   ([1](zotero://open-pdf/library/items/BTZRZZ8W?page=1&annotation=N6JLPBP7))
	
- "at alternates between sampling and optimization. Implementations that use automatic differentiation software work by constructing an objective function whose gradient is the policy gradient estimator; the estimator" | <mark style="background: #ff6666">Highlight</mark>   ([2](zotero://open-pdf/library/items/BTZRZZ8W?page=2&annotation=ENGESZDU))
	
- "s (see Section 6.1; results are not shown but were similar or worse than the “no clipping or penalty” setting). 2.2 Trust" | <mark style="background: #ffd400">Highlight</mark>   ([2](zotero://open-pdf/library/items/BTZRZZ8W?page=2&annotation=X6IBWUL7))
	
![[media/zotero/schulmanProximalPolicyOptimization2017/schulmanProximalPolicyOptimization2017-2-x146-y224.png]]
	
		- very interesting
	
