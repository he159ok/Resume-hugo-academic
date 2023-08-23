---
title: "CLUR: Uncertainty Estimation for Few-Shot Text Classification with
  Contrastive Learning"
publication_types:
  - "1"
authors:
  - J.He
  - X. Zhang
  - S. Lei
  - F. Chen
  - A. Alhamadani
  - B. Xiao
  - C. Lu.
publication_short: ""
abstract: |-
  Few-shot text classification has extensive application where the
  sample collection is expensive or complicated. When the penalty
  for classification errors is high, such as early threat event detection
  with scarce data, we expect to know “whether we should trust the
  classification results or reexamine them.” This paper investigates the
  Uncertainty Estimation for Few-shot Text Classification (UEFTC),
  an unexplored research area. Given limited samples, a UEFTC model
  predicts an uncertainty score for a classification result, which is
  the likelihood that the classification result is false. However, many
  traditional uncertainty estimation models in text classification are
  unsuitable for implementing a UEFTC model. These models require
  numerous training samples, whereas the few-shot setting in UEFTC
  only provides a few or just one support sample for each class in
  an episode. We propose Contrastive Learning from Uncertainty
  Relations (CLUR) to address UEFTC. CLUR can be trained with
  only one support sample for each class with the help of pseudo
  uncertainty scores. Unlike previous works that manually set the
  pseudo uncertainty scores, CLUR self-adaptively learns them using
  our proposed uncertainty relations. Specifically, we explore four
  model structures in CLUR to investigate the performance of three
  common-used contrastive learning components in UEFTC and find
  that two of the components are effective. 
draft: false
featured: true
tags:
  - Few-shot Uncertainty Estimation
slides: ""
url_pdf: ""
image:
  caption: ""
  focal_point: ""
  preview_only: false
  filename: featured.png
summary: ""
url_dataset: https://github.com/wowchemy/wowchemy-hugo-themes
url_project: ""
url_source: https://github.com/wowchemy/wowchemy-hugo-themes
url_video: https://youtube.com
author_notes: []
doi: ""
publication: In *SIGKDD 2023 (research track)*
projects: []
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
