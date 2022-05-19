---
title: Few-Shot Wild Animal Classification
summary: Used pretrained vision models for few-shot transfer learning to wild animal species classification on a dataset of ~40 species with ~7 training images of each. Performed an analysis of the impact of this work with respect to achieving sustainable development goals.
tags:
  - Deep Learning
date: '2022-04-01T00:00:00Z'

# Optional external URL for project (replaces project detail page).
external_link: ''

image:
  caption: Animal Classifier
  focal_point: Smart

links:
#  - icon: twitter
#    icon_pack: fab
#    name: Follow
#    url: https://twitter.com/georgecushen
url_code: 'https://colab.research.google.com/drive/1642Ok18XjggQmJ0hz9pf4lY_1VMCNMcl'
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

The challenge of tracking species numbers and locations is critical to ensuring that progress is made towards SDGs 14 (Life Below Water) and 15 (Life on Land). Delving into SDG 15, target 15.5 seeks to "halt the loss of biodiversity and prevent the extinction of threatened species", whilst target 15.8 aims to "prevent the introduction and significantly reduce the impact of invasive alien species on land and water ecosystems and control or eradicate the priority species". Having granular and accurate information on how species numbers or the locations in which they are found are changing over time is central to being able to address these targets.

Today, smartphones and other digital cameras are commonly held worldwide, meaning that a service such as iNaturalist can generate vast quantities of crowdsourced images and identifications of species that can help ecologists track species populations. However, identifying a species often requires more expertise than photographing one and images on iNaturalist need at least two equivalent user identifications to be given a species label. As such, many images on the platform go unidentified for some time. Automated species classification systems, such as the one built and evaluated above, could therefore be used to immediately classify species from new images at scale. Perhaps, given that there is still plenty of room for improvement in the performance of the model built in this work, these could serve as provisional labels until humans get round to identifying the species in a given image. Furthermore, camera traps are commonly used to capture images of wildlife. The same AI technologies that were used here could be additionally applied to this and other sources of image data.

From my analyses, I have seen that even with only a few examples of new classes, pretrained vision models can be positively transferred to give reasonably good results on limited datasets. This is helped further by supplementing the real dataset with augmented variations of the images within it. This means that resource and/or data constrained individuals and organisations can still utilise modern machine learning tools to have a positive impact on sustainable development goals related to conservation and biodiversity.
