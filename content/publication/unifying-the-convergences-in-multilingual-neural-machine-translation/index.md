---
title: Unifying the Convergences in Multilingual Neural Machine Translation
publication_types:
  - "1"
authors:
  - admin
  - Xiaocheng Feng
  - Xinwei Geng
  - Bing Qin
publication: EMNLP2022
abstract: Although all-in-one-model multilingual neural machine translation
  (MNMT) has achieved remarkable progress, the convergence inconsistency in the
  joint training is ignored, i.e.,different language pairs reaching convergence
  in different epochs. This leads to the trained MNMT model over-fitting
  low-resource language translations while under-fitting high-resource ones. In
  this paper, we propose a novel training strategy named LSSD (LanguageSpecific
  Self-Distillation), which can alleviate the convergence inconsistency and help
  MNMT models achieve the best performance on each language pair simultaneously.
  Specifically, LSSD picks up language-specific best checkpoints for each
  language pair to teach the current model on the fly. Furthermore, we
  systematically explore three sample-level manipulations of knowledge
  transferring. Experimental results on three datasets show that LSSD obtains
  consistent improvements towards all language pairs and achieves the
  state-of-the-art.
draft: false
featured: false
image:
  filename: featured
  focal_point: Smart
  preview_only: false
date: 2022-11-29T08:49:40.056Z
---
