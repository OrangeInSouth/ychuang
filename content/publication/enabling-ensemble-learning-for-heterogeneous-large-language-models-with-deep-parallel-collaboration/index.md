---
title: Enabling Ensemble Learning for Heterogeneous Large Language Models with
  Deep Parallel Collaboration
publication_types:
  - "1"
authors:
  - "*Yichong Huang*"
  - Xiaocheng Feng
  - Baohang Li
  - Yang Xiang
  - Hui Wang
  - Bing Qin
  - Ting Liu
publication_short: Under Review
abstract: Large language models (LLMs) have shown complementary strengths in
  various tasks and instances, motivating the research of ensembling LLMs to
  push the frontier leveraging the wisdom of the crowd. Existing work achieves
  this objective via training the extra reward model or fusion model to select
  or fuse all candidate answers. However, these methods pose a great challenge
  to the generalizability of the trained models. Besides, existing methods use
  the textual responses as communication media, ignoring the rich information in
  the inner representations of neural networks. Therefore, we propose a
  training-free ensemble framework DeePEn, averaging the probability
  distributions outputted by different LLMs. A key challenge in this paradigm is
  the vocabulary discrepancy between heterogeneous LLMs, which hinders the
  operation of probability distribution averaging. To address this challenge,
  DeePEn maps the probability distribution of each model from the probability
  space to a universe relative space based on the relative representation
  theory, and performs aggregation. Then, the result of aggregation is mapped
  back to the probability space of one LLM via a search-based inverse
  transformation to determine the generated token. We conduct experiments on the
  ensemble of various LLMs of 6B to 70B. Experimental results show that DeePEn
  achieves consistent improvements across six popular benchmarks involving
  subject examination, reasoning and knowledge-QA, proving the effectiveness of
  our approach.
draft: false
featured: false
image:
  filename: featured
  focal_point: Smart
  preview_only: false
date: 2024-02-20T12:56:33.336Z
---
