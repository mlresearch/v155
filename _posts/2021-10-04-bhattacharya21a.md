---
title: Multiagent Rollout and Policy Iteration for POMDP with Application to Multi-Robot
  Repair Problems
abstract: 'In this paper we consider infinite horizon discounted dynamic programming
  problems with finite state and control spaces, partial state observations, and a
  multiagent structure. We discuss and compare algorithms that simultaneously or sequentially
  optimize the agents’ controls by using multistep lookahead, truncated rollout with
  a known base policy, and a terminal cost function approximation. Our methods specifically
  address the computational challenges of partially observable multiagent problems.
  In particular: 1) We consider rollout algorithms that dramatically reduce required
  computation while preserving the key cost improvement property of the standard rollout
  method. The per-step computational requirements for our methods are on the order
  of $O(Cm)$ as compared with $O(C^m)$ for standard rollout, where $C$ is the maximum
  cardinality of the constraint set for the control component of each agent, and $m$
  is the number of agents. 2) We show that our methods can be applied to challenging
  problems with a graph structure, including a class of robot repair problems whereby
  multiple robots collaboratively inspect and repair a system under partial information.
  3) We provide a simulation study that compares our methods with existing methods,
  and demonstrate that our methods can handle larger and more complex partially observable
  multiagent problems (state space size $10^{37}$ and control space size $10^{7}$,
  respectively). In particular, we verify experimentally that our multiagent rollout
  methods perform nearly as well as standard rollout for problems with few agents,
  and produce satisfactory policies for problems with a larger number of agents that
  are intractable by standard rollout and other state of the art methods. Finally,
  we incorporate our multiagent rollout algorithms as building blocks in an approximate
  policy iteration scheme, where successive rollout policies are approximated by using
  neural network classifiers. While this scheme requires a strictly off-line implementation,
  it works well in our computational experiments and produces additional significant
  performance improvement over the single online rollout iteration method.'
paperid: '416'
layout: inproceedings
series: Proceedings of Machine Learning Research
publisher: PMLR
issn: 2640-3498
id: bhattacharya21a
month: 0
tex_title: Multiagent Rollout and Policy Iteration for POMDP with Application to Multi-Robot
  Repair Problems
firstpage: 1814
lastpage: 1828
page: 1814-1828
order: 1814
cycles: false
bibtex_author: Bhattacharya, Sushmita and Kailas, Siva and Badyal, Sahil and Gil,
  Stephanie and Bertsekas, Dimitri
author:
- given: Sushmita
  family: Bhattacharya
- given: Siva
  family: Kailas
- given: Sahil
  family: Badyal
- given: Stephanie
  family: Gil
- given: Dimitri
  family: Bertsekas
date: 2021-10-04
address:
container-title: Proceedings of the 2020 Conference on Robot Learning
volume: '155'
genre: inproceedings
issued:
  date-parts:
  - 2021
  - 10
  - 4
pdf: https://proceedings.mlr.press/v155/bhattacharya21a/bhattacharya21a.pdf
extras: []
# Format based on citeproc: http://blog.martinfenner.org/2013/07/30/citeproc-yaml-for-bibliographies/
---
