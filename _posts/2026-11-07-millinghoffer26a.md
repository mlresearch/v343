---
title: 'LOCO-FL: Scaling and Reference Choice for Bayesian Structural Analysis of
  Between-Center Heterogeneity in Federated Learning with Markov Boundaries'
section: papers
abstract: 'Multicenter quality-improvement programs still struggle to explain between-center
  heterogeneity using outcome measures alone. We investigate a Bayesian network method
  that focuses on Markov boundaries to characterize this heterogeneity at the structural
  level of risk models with multiple outcomes. Working with the full structure posterior
  rather than a point estimate allows the study of a phenomenon that point-identification
  learners overlook: under proper regularization, the resolvable Markov-boundary complexity
  grows with sample size. A naive comparison across centers, therefore, mixes sample-size
  induced model properties with genuine structural differences. We therefore study
  a global reference versus leave-one-center-out (LOCO) references together with sample-size
  correction, and show that both can be analyzed within a single reweighting of the
  per-family BD sufficient statistics, achieved exactly by adding the $\beta$-scaled
  LOCO counts as pseudocounts to the score. We investigate augmenting small centers
  to a larger, common effective size using the LOCO sample. We present two exact,
  privacy-preserving (PP) Bayesian federated learning schemes: a single global-reference
  scheme and a LOCO-reference scheme (LOCO-FL). We show that the LOCO-FL scheme supports
  per-center reference comparison and per-center scaling under the same institutional-privacy
  guarantees. Because the LOCO aggregate excludes a center’s own data, the same LOCO
  counts can also serve as an informative prior for that center’s local inference,
  without self-inclusion. We choose the scale of this prior empirically, as the value
  that most reduces the posterior spread, which reveals a trade-off between variance
  reduction and loss of the between-center signal. On synthetic data with known between-center
  differences, the method recovers these differences above the within-posterior spread.
  We report results for an eight-center Hungarian very preterm cohort (2{,}939 patients),
  measuring heterogeneity by posterior Jaccard distances between LOCO and global references.
  Results confirm the need to scale to a common effective sample size, the utility
  of a single global reference for coarse comparison, and that an empirically scaled
  LOCO prior reduces posterior spread.'
layout: inproceedings
series: Proceedings of Machine Learning Research
publisher: PMLR
issn: 2640-3498
id: millinghoffer26a
month: 0
tex_title: "{LOCO-FL}: Scaling and Reference Choice for {Bayesian} Structural Analysis
  of Between-Center Heterogeneity in Federated Learning with {Markov} Boundaries"
firstpage: 646
lastpage: 662
page: 646-662
order: 646
cycles: false
bibtex_author: Millinghoffer, Andr\'as and Kisida, J\'ulia and Valek, Andrea and Szab\'o,
  Mikl\'os and Antal, P\'eter
author:
- given: András
  family: Millinghoffer
- given: Júlia
  family: Kisida
- given: Andrea
  family: Valek
- given: Miklós
  family: Szabó
- given: Péter
  family: Antal
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
pdf: https://raw.githubusercontent.com/mlresearch/v343/main/assets/millinghoffer26a/millinghoffer26a.pdf
extras: []
# Format based on Martin Fenner's citeproc: https://blog.front-matter.io/posts/citeproc-yaml-for-bibliographies/
---
