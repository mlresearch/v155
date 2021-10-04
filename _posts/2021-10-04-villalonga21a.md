---
title: Tactile Object Pose Estimation from the First Touch with Geometric Contact
  Rendering
abstract: In this paper, we present an approach to tactile pose estimation from the
  first touch for known objects. First, we create an object-agnostic map from real
  tactile observations to contact shapes. Next, for a new object with known geometry,
  we learn a tailored perception model completely in simulation. To do so, we simulate
  the contact shapes that a dense set of object poses would produce on the sensor.
  Then, given a new contact shape obtained from the sensor output, we match it against
  the pre-computed set using the object-specific embedding learned purely in simulation
  using contrastive learning. This results in a perception model that can localize
  objects from a single tactile observation. It also allows reasoning over pose distributions
  and including additional pose constraints coming from other perception systems or
  multiple contacts. We provide quantitative results for four objects. Our approach
  provides high accuracy pose estimations from distinctive tactile observations while
  regressing pose distributions to account for those contact shapes that could result
  from different object poses. We further extend and test our approach in multi-contact
  scenarios where several tactile sensors are simultaneously in contact with the object.
paperid: '213'
layout: inproceedings
series: Proceedings of Machine Learning Research
publisher: PMLR
issn: 2640-3498
id: villalonga21a
month: 0
tex_title: Tactile Object Pose Estimation from the First Touch with Geometric Contact
  Rendering
firstpage: 1015
lastpage: 1029
page: 1015-1029
order: 1015
cycles: false
bibtex_author: Villalonga, Maria Bauza and Rodriguez, Alberto and Lim, Bryan and Valls,
  Eric and Sechopoulos, Theo
author:
- given: Maria Bauza
  family: Villalonga
- given: Alberto
  family: Rodriguez
- given: Bryan
  family: Lim
- given: Eric
  family: Valls
- given: Theo
  family: Sechopoulos
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
pdf: https://proceedings.mlr.press/v155/villalonga21a/villalonga21a.pdf
extras: []
# Format based on citeproc: http://blog.martinfenner.org/2013/07/30/citeproc-yaml-for-bibliographies/
---
