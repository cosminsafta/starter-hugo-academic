---
title: Graph Neural Network Models
summary: Graph Neural Network Models of Complex Initial Boundary Value Problems that embed Physical Invariances
tags:
date: "2022-03-20"

# Optional external URL for project (replaces project detail page).
external_link: ""

image:
  caption: Graph Convolutional Neural Network
  focal_point: Smart

#links:
#- icon: twitter
#  icon_pack: fab
#  name: Follow
#  url: https://twitter.com/georgecushen
#url_code: ""
#url_pdf: ""
#url_slides: ""
#url_video: ""

# Slides (optional).
#   Associate this project with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides = "example-slides"` references `content/slides/example-slides.md`.
#   Otherwise, set `slides = ""`.
#slides: example
---
We develop graph-based convolutional neural networks to provide efficient homogenized surrogate and full-field models for a wide class of physical problems that involve complex initial states. Graph neural networks have advantages over the more established neural network architectures that have been applied to physical problems. Specifically, we will embed spatially invariant and conserving feature representations and filters into graph architectures. This aspect will reduce the raw high-fidelity mesh inputs to more compact, low-rank manifolds since the symmetries will constrain the manifolds of features related to the chosen outputs. More broadly, our machine learning approach will be guided by expert knowledge from a multitude of more mature fields of mathematical and physical science, including signal processing and representation theory. This guided but still general learning framework should be more generalizable and more interpretable than standard approaches.