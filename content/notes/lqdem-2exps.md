---
title: "Liquid Democracy: Two Experiments on Delegation in Voting"
date: 2023-03-23
tags:
- democracy
---

[paper](https://www.nber.org/system/files/working_papers/w30794/w30794.pdf?curius=2726)
- **primary concern**: are experts correctly identified?
- common interests model:
	- voters receive independent signals; ex ante equal prob one of two values
	- common objective: identify state correctly via majority vote
	- signal *precision* (probability of correctness) varies across individuals
	- experts publicly identified, precision of their signals public info
	- voter precision private info, weakly lower than experts
	- if voter delegates, vote is randomly assigned to one of the experts (weird)

## theoretical results
- equilibrium w/ positive delegation that dominates majority voting w/o delegation. however, over-delegation is costly; should only delegate when own precision close to random
	- if $\pi = Pr ( \omega_1 ) = \frac{1}{2}$  for any $F$ and for any odd $N$ and $K$ there exists an equilibrium with delegation that strictly improves over $MV$
- incorrectly choosing precision threshold at which to delegate incurs high cost; worse for LD vs MVA
- blue: LD, green: MVA; X: delegation / abstention precision threshold, Y: $\mathbb{E}[U]$![[notes/images/ld.png]]
- 

## experiments
- experiment 1
	1. liquid dem (LD)
	2. majority vote w/ abstention (MVA) abstention replaces delegation
	3. simple majority voting
	- two settings: 5 voters 1 expert, 15 voters 3 experts
	- dependent var: freq of delegation & fraction of decisions yielding correct outcome
- results: systemic over-delegation (2 - 3x unique strict equilibrium)
- experiment 2
	- methodological variant using [Random Dot Kinematograms](https://www.youtube.com/watch?v=7OdCe95IiLw) trying to correct bias due to overly mathematical task presentation to subjects
	
## critique
- LD proposes improvement over representative democracy under the assumption that not all proposals can tractably be taken to referendum (MV does not stale to large numbers of issues)
- the authors demonstrate marginal improvement of LD over MV, then illustrate that humans tend to over-delegate under LD, undermining its theoretical equilibrium advantage
- the authors conclude that a simpler solution (given common interests) is majority voting with abstention
- the paper does not consider:
	1. representational democracy (the failures of which LD is attempting to solve)
	2. mis-aligned values / plurality of interests
- common interests is generally a bad model for the types of problems democracies usefully solve:  referendum usually involves some contentious issue w/ (real or perceived) potential harm to some subset of the electorate
- dynamics observed in common interest studies are unlikely to generalize
- assumes one-dimensional assessment of representatives (precision)
- improvement: vary degree of contention (mixed objectives by ratio)
- reps should to be assessed on 2 axes: expertise *and* alignment (thoughts on addressing this in [[thoughts/democracy#idea-bellman-delegation|bellman delegation]])