---
title: The Emergence of Adversarial Communication in Multi-Agent Reinforcement Learning
abstract: Many real-world problems require the coordination of multiple autonomous
  agents. Recent work has shown the promise of Graph Neural Networks (GNNs) to learn
  explicit communication strategies that enable complex multi-agent coordination.
  These works use models of cooperative multi-agent systems whereby agents strive
  to achieve a shared global goal. When considering agents with self-interested local
  objectives, the standard design choice is to model these as separate learning systems
  (albeit sharing the same environment). Such a design choice, however, precludes
  the existence of a single, differentiable communication channel, and consequently
  prohibits the learning of inter-agent communication strategies. In this work, we
  address this gap by presenting a learning model that accommodates individual non-shared
  rewards and a differentiable communication channel that is common among all agents.
  We focus on the case where agents have self-interested objectives, and develop a
  learning algorithm that elicits the emergence of adversarial communications. We
  perform experiments on multi-agent coverage and path planning problems, and employ
  a post-hoc interpretability technique to visualize the messages that agents communicate
  to each other. We show how a single self-interested agent is capable of learning
  highly manipulative communication strategies that allows it to significantly outperform
  a cooperative team of agents.
paperid: '306'
layout: inproceedings
series: Proceedings of Machine Learning Research
publisher: PMLR
issn: 2640-3498
id: blumenkamp21a
month: 0
tex_title: The Emergence of Adversarial Communication in Multi-Agent Reinforcement
  Learning
firstpage: 1394
lastpage: 1414
page: 1394-1414
order: 1394
cycles: false
bibtex_author: Blumenkamp, Jan and Prorok, Amanda
author:
- given: Jan
  family: Blumenkamp
- given: Amanda
  family: Prorok
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
pdf: https://proceedings.mlr.press/v155/blumenkamp21a/blumenkamp21a.pdf
extras: []
# Format based on citeproc: http://blog.martinfenner.org/2013/07/30/citeproc-yaml-for-bibliographies/
---
