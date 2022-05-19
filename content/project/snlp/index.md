---
title: Debiasing Toxic Language Classifiers
summary: Created a method for minimising identity-related biases in toxic language classifiers by manipulating the sentence embeddings of online comments.
tags:
  - Deep Learning
date: '2022-05-01T00:00:00Z'

# Optional external URL for project (replaces project detail page).
external_link: ''

image:
  caption: Spreading Tweet
  focal_point: Smart

links:
#  - icon: twitter
#    icon_pack: fab
#    name: Follow
#    url: https://twitter.com/georgecushen
url_code: 'https://github.com/williambankes/COMP0087'
url_pdf: 'https://drive.google.com/file/d/1zkiLpSrqZaNJGxizb-QOqC4bb9uW3xtJ/view?usp=sharing'
url_slides: ''
url_video: ''

# Slides (optional).
#   Associate this project with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides = "example-slides"` references `content/slides/example-slides.md`.
#   Otherwise, set `slides = ""`.
#   slides: example
---

Toxicity pervades many Internet platforms, making services designed to connect, inform and entertain unsafe and potentially harmful. In an effort to tackle this problem, natural language processing methods have been used to partially, or fully automate the process of detecting toxic language. These approaches have been shown to exhibit identity bias by over-attributing toxicity to language associated with discriminated or marginalised identities. We address this pitfall by first analysing the impact of identity-specific vocabulary on the toxicity predictions of a neural network. We then present two novel methods for debiasing these predictions, both centred around perturbing sentence embeddings for text that contains identity labels. Through our analyses, we show that such an approach can be effective at mitigating the aforementioned biases in toxicity predictions on some simple sentences, but that this does performance does not necessarily translate to a skewed real-world dataset that comprises complicated comments. 
