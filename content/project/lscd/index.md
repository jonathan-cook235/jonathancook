---
title: Leveraging Time-Dependent Lexical Features for Offensive Language Detection
summary: Built a deep learning model for lexical semantic change detection (i.e., the detection of changes in word meanings) and used its predictions, along with other time-varying lexical and statistical language features, as additional inputs into another neural network that performs offensive language detection.
tags:
  - NLP
date: '2021-11-01T00:00:00Z'

# Optional external URL for project (replaces project detail page).
external_link: ''

image:
  caption: Offensive Language
  focal_point: Smart

links:
#  - icon: twitter
#    icon_pack: fab
#    name: Follow
#    url: https://twitter.com/georgecushen
url_code: 'https://github.com/jonathan-cook235/AlanTuringInstitute-Offenseval-Semantic-Change'
url_pdf: ''
url_slides: ''
url_video: ''

# Slides (optional).
#   Associate this project with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides = "example-slides"` references `content/slides/example-slides.md`.
#   Otherwise, set `slides = ""`.
#   slides: example
---

We present a new methodology for improving the performance of lexicon-based offensive language detection systems. Our focus is on Offenseval sub-task A, aimed at detecting offensive tweets. We train an SVM classifier on the Offenseval 2019 training set. Using a combination of statistical features and lexical features, we build on the SINAI system submitted to Offenseval 2019. We add new lexical features, including features that capture the change in usage of words between 2019 and 2020, and specifically their association with emerging offensive usages. Our model is shown to perform better than the original system, with its performance being comparable to SINAI trained on 2020 training data. Our work draws attention to an often neglected aspect of offensive language, namely that the meanings of words are constantly evolving and that NLP systems relying that account for this change can achieve good performance even when not trained on the most recent training data. 
