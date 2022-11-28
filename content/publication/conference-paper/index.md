---
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
slides: example
url_pdf: ""
publication_types:
  - "1"
authors:
  - admin
author_notes: []
publication: In *EMNLP2022*
summary: Lorem ipsum dolor sit amet, consectetur adipiscing elit. Duis posuere
  tellus ac convallis placerat. Proin tincidunt magna sed ex sollicitudin
  condimentum.
url_dataset: https://github.com/wowchemy/wowchemy-hugo-themes
url_project: ""
publication_short: ""
url_source: https://github.com/wowchemy/wowchemy-hugo-themes
url_video: https://youtube.com
title: Unifying the Convergences in Multilingual Neural Machine Translation
doi: ""
featured: true
tags: []
projects:
  - example
image:
  caption: ""
  focal_point: ""
  preview_only: false
date: 2013-07-01T00:00:00.000Z
url_slides: ""
publishDate: 2017-01-01T00:00:00.000Z
url_poster: ""
url_code: https://github.com/wowchemy/wowchemy-hugo-themes
---

{{% callout note %}}
Click the _Cite_ button above to demo the feature to enable visitors to import publication metadata into their reference management software.
{{% /callout %}}

{{% callout note %}}
Create your slides in Markdown - click the _Slides_ button to check out the example.
{{% /callout %}}

Supplementary notes can be added here, including [code, math, and images](https://wowchemy.com/docs/writing-markdown-latex/).
