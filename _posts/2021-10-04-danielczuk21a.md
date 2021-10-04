---
title: 'Exploratory Grasping: Asymptotically Optimal Algorithms for Grasping Challenging
  Polyhedral Objects'
abstract: There has been significant recent work on data-driven algorithms for learning
  general-purpose grasping policies.  However, these policies can consistently fail
  to grasp challenging objects which are significantly out of the distribution of
  objects in the training data or which have very few high quality grasps. Motivated
  by such objects, we propose a novel problem setting, Exploratory Grasping, for efficiently
  discovering reliable grasps on an unknown polyhedral object via sequential grasping,
  releasing, and toppling. We formalize Exploratory Grasping as a Markov Decision
  Process where we assume that the robot can (1) distinguish stable poses of a polyhedral
  object of unknown geometry, (2) generate grasp candidates on these poses and execute
  them, (3) determine whether each grasp is successful, and (4) release the object
  into a random new pose after a grasp successor topple the object after a grasp failure.  We
  study the theoretical complexity of Exploratory Grasping in the context of reinforcement
  learning and present an efficient bandit-style algorithm, Bandits for Online Rapid
  Grasp ExplorationStrategy (BORGES), which leverages the structure of the problem
  to efficiently discover high performing grasps for each object stable pose. BORGES
  can be used to complement any general-purpose grasping algorithm with any grasp
  modality (parallel-jaw, suction, multi-fingered, etc) to learn policies for objects
  in which they exhibit persistent failures. Simulation experiments suggest that BORGES
  can significantly outperform both general-purpose grasping pipelines and two other
  online learning algorithms and achieves performance within 5% of the optimal policy
  within 1000 and 8000 timesteps on average across 46 challenging objects from the
  Dex-Net adversarial and EGAD! object datasets, respectively. Initial physical experiments
  suggesting that BORGES can improve grasp success rate on average over two challenging
  3D printed objects by 45% over a Dex-Net baseline. See https://tinyurl.com/exp-grasping
  for supplementary material and videos.
paperid: '79'
layout: inproceedings
series: Proceedings of Machine Learning Research
publisher: PMLR
issn: 2640-3498
id: danielczuk21a
month: 0
tex_title: 'Exploratory Grasping: Asymptotically Optimal Algorithms for Grasping Challenging
  Polyhedral Objects'
firstpage: 377
lastpage: 393
page: 377-393
order: 377
cycles: false
bibtex_author: Danielczuk, Michael and Balakrishna, Ashwin and Brown, Daniel and Goldberg,
  Ken
author:
- given: Michael
  family: Danielczuk
- given: Ashwin
  family: Balakrishna
- given: Daniel
  family: Brown
- given: Ken
  family: Goldberg
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
pdf: https://proceedings.mlr.press/v155/danielczuk21a/danielczuk21a.pdf
extras: []
# Format based on citeproc: http://blog.martinfenner.org/2013/07/30/citeproc-yaml-for-bibliographies/
---
