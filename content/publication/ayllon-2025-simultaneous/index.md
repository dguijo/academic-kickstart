---
# Documentation: https://sourcethemes.com/academic/docs/managing-content/

title: Simultaneous multi-step wind speed prediction on multiple farms using multi-task
  deep learning
subtitle: ''
summary: ''
authors:
- Rafael Ayllón-Gavilán
- Antonio Manuel Gómez-Orellana
- Víctor Manuel Vargas
- David Guijo-Rubio
- Jorge Pérez-Aracil
- Sancho Salcedo-Sanz
- Pedro Antonio Gutiérrez
- César Hervás-Martínez
tags: []
categories: []
date: '2025-05-01'
lastmod: 2025-08-18T13:44:09+02:00
featured: false
draft: false

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder.
# Focal points: Smart, Center, TopLeft, Top, TopRight, Left, Right, BottomLeft, Bottom, BottomRight.
image:
  caption: ''
  focal_point: ''
  preview_only: false

# Projects (optional).
#   Associate this post with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `projects = ["internal-project"]` references `content/project/deep-learning/index.md`.
#   Otherwise, set `projects = []`.
projects: []
publishDate: '2025-08-18T11:44:09.369904Z'
publication_types:
- '2'
abstract: 'In this paper, we present the MUSONet model, which leverages information
  from different sources (in this case, wind farms) to perform a multi-step wind speed
  prediction. The main goal of this approach is improving the global prediction accuracy,
  specifically at longer prediction horizons. Thus, the proposed model is able to
  simultaneously predict the wind speed at three different prediction horizons (6h,
  12h, and 24h), across three different wind farms located in Spain. We also evaluate
  the performance of the presented methodology by considering three different activation
  functions for hidden neurons in the neural network: Sigmoid, ReLU, and ELUs+2L.
  The results show that the proposed multi-source approach improves the performance
  of the single-source counterpart for the longer prediction horizons (12h and 24h).
  In addition, the proposed multi-source method reduces by over 30 % the number of
  parameters compared to three single-source models (in this case, one model per wind
  farm), resulting in a simpler solution for the problem addressed and requiring much
  lower computational resources.'
publication: '*Integrated Computer-Aided Engineering*'
doi: 10.1177/10692509251337224
links:
- name: URL
  url: https://journals.sagepub.com/doi/full/10.1177/10692509251337224
---
