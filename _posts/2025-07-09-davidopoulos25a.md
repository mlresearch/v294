---
title: Individual Fairness in Algorithmic Hiring
openreview: cGoSFlnar5
abstract: In this paper, we study individual fairness in job recommendations, and
  make two concrete contributions. To the best of our knowledge, we are the first
  to introduce the concept of $\varepsilon$-individual fairness to job recommendations;
  the smaller the value of $\varepsilon$, the stronger the guarantee of individual
  fairness is. Compared to existing definitions of individual fairness, e.g., for
  classification tasks, the output of a recommender is a ranked list of items, here
  jobs. Therefore, the novel aspect is that we propose the use of Kendall’s $\tau$
  distance as a measure of similarity between recommendation lists. To ensure individual
  fairness, we introduce a novel post-processing approach. Initially, we cluster individuals
  with similar non-protected attributes. For each cluster, we construct a Kemeny-optimal
  aggregate recommendation list, which will serve as a template to generate individual
  recommendations. As a result, similar individuals will receive similar recommendations.
  Our experiments show that our method can effectively control the individual fairness
  guarantee, i.e., the value of $\varepsilon$.
section: Extended Abstracts
layout: inproceedings
series: Proceedings of Machine Learning Research
publisher: PMLR
issn: 2640-3498
id: davidopoulos25a
month: 0
tex_title: Individual Fairness in Algorithmic Hiring
firstpage: 505
lastpage: 510
page: 505-510
order: 505
cycles: false
bibtex_author: Davidopoulos, Stavros and Symeonidis, Panagiotis and Sacharidis, Dimitris
author:
- given: Stavros
  family: Davidopoulos
- given: Panagiotis
  family: Symeonidis
- given: Dimitris
  family: Sacharidis
date: 2025-07-09
address:
container-title: Proceedings of Fourth European Workshop on Algorithmic Fairness
volume: '294'
genre: inproceedings
issued:
  date-parts:
  - 2025
  - 7
  - 9
pdf: https://raw.githubusercontent.com/mlresearch/v294/main/assets/davidopoulos25a/davidopoulos25a.pdf
extras: []
# Format based on Martin Fenner's citeproc: https://blog.front-matter.io/posts/citeproc-yaml-for-bibliographies/
---
