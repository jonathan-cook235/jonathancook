---
title: Mapping the World's Offline Population
summary: Setup an open-source data gathering pipeline to gather Internet connectivity predictors and used proprietary survey data provided by several national governments as ground-truth labels. Built and compared various machine learning models to predict the presence of offline populations using this data. Deployed the best-performing model, for use by the UN's International Telecommunications Union and UNICEF, and presented findings to affiliated national governments.
tags:
  - Other
date: '2021-06-01T00:00:00Z'

# Optional external URL for project (replaces project detail page).
external_link: ''

image:
  caption: Giga
  focal_point: Smart

links:
#  - icon: twitter
#    icon_pack: fab
#    name: Follow
#    url: https://twitter.com/georgecushen
url_code: 'https://github.com/jonathan-cook235/DSSGxUK-ITU'
url_docs: 'https://dssgxuk.github.io/itu/'
url_slides: ''
url_video: ''

# Slides (optional).
#   Associate this project with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides = "example-slides"` references `content/slides/example-slides.md`.
#   Otherwise, set `slides = ""`.
#   slides: example
---

This project develops a predictive model to estimate the number of people connected to the internet (internet, in this instance, is a proxy for access to social and economic opportunities). The model was trained on a combination of survey data and multiple open source datasets. With the help of the custom engineered data gathering pipeline, the open source data can be collected for any given country and either the existing model can be applied or a new model can be trained if survey data is available.

This project was built from June - August 2021 and is a collaboration between the Data Science for Social Good Fellowship at the University of Warwick, UK and the International Telecommunications Union, a UN Agency.
