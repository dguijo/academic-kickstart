---
# Documentation: https://sourcethemes.com/academic/docs/managing-content/

title: 'ORFEO: Ordinal classifier and Regressor Fusion for Estimating an Ordinal categorical
  target'
subtitle: ''
summary: ''
authors:
- Antonio Manuel Gómez-Orellana
- David Guijo-Rubio
- Pedro Antonio Gutiérrez
- César Hervás-Martínez
- Víctor Manuel Vargas
tags:
- Ordinal classification
- Neural networks
- Cumulative link models
- Short-term prediction
- Significant wave height
- Flux of energy
- Loss functions
categories: []
date: '2024-07-01'
lastmod: 2024-05-20T10:55:09+02:00
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
publishDate: '2024-05-20T08:55:08.960463Z'
publication_types:
- '2'
abstract: 'In this paper we present a novel methodology, referenced as ORFEO (Ordinal
  classifier and Regressor Fusion for Estimating an Ordinal categorical target), to
  enhance the performance in ordinal classification problems for which the latent
  variable is observable. ORFEO is an artificial neural network model incorporating
  two outputs, one for ordinal classification, using the cumulative link model, and
  one for regression, using a linear model. Both outputs are simultaneously optimised
  considering a loss function that linearly combines both classification and regression
  losses. The main motivation behind developing the proposed approach is to enhance
  the performance of a standard ordinal classifier. This improvement is facilitated
  by considering the regression output, which allows the model to differentiate between
  patterns within the same category. The ORFEO model is applied to two problems in
  the field of marine and ocean engineering: short-term prediction of both significant
  wave height and flux of energy. Both problems are addressed considering four different
  coastal zones of the United States of America, using 13 datasets formed by buoys
  measurements and reanalysis data. A comprehensive comparison against 20 methodologies,
  including regression and nominal/ordinal classification approaches is performed,
  by using diverse nominal and ordinal performance metrics. Ranks achieved indicate
  that ORFEO outperforms all the compared methodologies in terms of all the performance
  measures, demonstrating the efficacy and robustness of the proposal. Finally, a
  statistical analysis is conducted, concluding that there are statistically significant
  differences across ordinal and nominal performance metrics in favour of the proposed
  ORFEO model.'
publication: '*Engineering Applications of Artificial Intelligence*'
doi: 10.1016/j.engappai.2024.108462
links:
- name: URL
  url: www.sciencedirect.com/science/article/pii/S0952197624006201?via%3Dihub
---
