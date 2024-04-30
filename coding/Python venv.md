---
publish: 
tags:
  - theory
  - coding
date: 2024-04-30
link:
---
# Introduction
- Venv module is used to creating lightweight "virtual environments", each with their own independent set of Python packages installed in their site directories.

# Used for
- Used to contain a specific Python interpreter and software libraries and binaries which are needed to support a project (library or application). These are by default isolated from software in other virtual environments and Python interpreters and libraries installed in the operating system.
- Contained in a directory, conventionally either named `venv` or `.venv` in the project directory, or under a container directory for lots of virtual environments, such as `~/.virtualenvs`.
- Not checked into source control systems such as Git.
- Considered as disposable – it should be simple to delete and recreate it from scratch. You don’t place any project code in the environment
- Not considered as movable or copyable – you just recreate the same environment in the target location.

# Usage
Creation of virtual environments is done by executing the command `venv`:

```bash 
python -m venv /path/to/venv/virtual/environment 
```

# Further Reading and Resources
- Thorough walk-through: https://docs.python.org/3/library/venv.html
