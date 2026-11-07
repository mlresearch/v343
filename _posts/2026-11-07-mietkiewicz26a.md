---
title: 'Gradient-Based Fine-Tuning of Expert Bayesian Network Classifiers: Application
  in Forensic Porcine Wound Age Assessment'
section: papers
abstract: Bayesian network classifiers built from expert knowledge encode valuable
  domain understanding but may be improved when labelled data become available. We
  propose \textsc{EB-GFTBN}, a Gradient-based Fine-Tuning algorithm for Bayesian Networks
  with Expert-Bounded parameter updates. Building on the fine-tuning framework of
  El Hindi (2014) and the Brier-score variant of Mietkiewicz and Madsen (2022), we
  derive natural-gradient updates from the derivative of the Brier score and extend
  the algorithm to mixed discrete–continuous Bayesian networks. To remain faithful
  to the expert specification, each parameter is constrained to a relative tolerance
  around its expert elicited value. The methodology is evaluated in a case study regarding
  forensic age assessment of porcine wounds, where the parameters of a Bayesian network
  classifier were elicited from veterinary experts. Across $100$ cross-validation
  folds, \textsc{EB-GFTBN} improves both accuracy and Brier score over the expert
  baseline and the penalised EM alternative, while keeping every parameter inside
  the expert-allowed window.
layout: inproceedings
series: Proceedings of Machine Learning Research
publisher: PMLR
issn: 2640-3498
id: mietkiewicz26a
month: 0
tex_title: 'Gradient-Based Fine-Tuning of Expert {Bayesian} Network Classifiers: Application
  in Forensic Porcine Wound Age Assessment'
firstpage: 629
lastpage: 645
page: 629-645
order: 629
cycles: false
bibtex_author: Mietkiewicz, Joseph and Madsen, Anders L and Nielsen, Thomas Dyhre
  and B{\ae}kg{\aa}rd, Cecilie and Jensen, Henrik Elvang and Barington, Kristiane
author:
- given: Joseph
  family: Mietkiewicz
- given: Anders L
  family: Madsen
- given: Thomas Dyhre
  family: Nielsen
- given: Cecilie
  family: Bækgård
- given: Henrik Elvang
  family: Jensen
- given: Kristiane
  family: Barington
date: 2026-11-07
address:
container-title: Proceedings of the 13th International Conference on Probabilistic
  Graphical Models
volume: '343'
genre: inproceedings
issued:
  date-parts:
  - 2026
  - 11
  - 7
pdf: https://raw.githubusercontent.com/mlresearch/v343/main/assets/mietkiewicz26a/mietkiewicz26a.pdf
extras: []
# Format based on Martin Fenner's citeproc: https://blog.front-matter.io/posts/citeproc-yaml-for-bibliographies/
---
