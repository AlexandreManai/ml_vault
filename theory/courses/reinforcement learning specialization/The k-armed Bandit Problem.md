---
publish: 
tags:
  - theory
  - reinforcementLearning
date: 2024-09-09
link: https://www.coursera.org/learn/fundamentals-of-reinforcement-learning/home/module/2
---
## Type of problem
**Tabular Solution Method**:
- core ideas of RL 
- *State and Action Spaces* are small enough to approximate *Value Functions* represented as arrays or *tables* ==> Able to find **Exact Solutions** == Find optimal **Value Function** and **Policy** 
- Larger Problems == More Complex / Bigger State and Action Spaces 
	- leading to the need for **Approximate Solutions**
- Single State == **Bandit Problem**

## Multi-armed Bandits
- RL uses training information that *evaluates* the actions taken rather than *instructs* by giving correct actions 
	- Even though bootstrapping the difficult start phase of unknown/fruitless trial and error with artificial knowledge could be beneficial
	- ==> Need some sort of **Exploration**

### k-armed Bandit Problem
