---
title: Towards Higher Pareto Frontier in Multilingual Machine Translation
publication_types:
  - "0"
  - "1"
authors:
  - Yichong Huang
  - Xiaocheng Feng
  - Xinwei Geng
  - Baohang Li
  - Bing Qin
publication: ACL2023
abstract: Multilingual neural machine translation has witnessed remarkable
  progress in recent years. However, the long-tailed distribution of
  multilingual corpora poses a challenge of Pareto optimization, i.e.,
  optimizing for some languages may come at the cost of degrading the
  performance of others. Existing balancing training strategies are equivalent
  to a series of Pareto optimal solutions, which trade off on a Pareto frontier.
  In this work, we propose a new training framework, Pareto Mutual Distillation
  (Pareto-MD), towards pushing the Pareto frontier outwards rather than making
  trade-offs. Specifically, Pareto-MD collaboratively trains two Pareto optimal
  solutions that favor different languages and allows them to learn from the
  strengths of each other via knowledge distillation. Furthermore, we introduce
  a novel strategy to enable stronger communication between Pareto optimal
  solutions and broaden the applicability of our approach. Experimental results
  on the widely-used WMT and TED datasets show that our method significantly
  pushes the Pareto frontier and outperforms baselines by up to +2.46 BLEU
draft: false
featured: false
image:
  filename: featured
  focal_point: Smart
  preview_only: false
date: 2023-11-26T01:36:39.496Z
---
