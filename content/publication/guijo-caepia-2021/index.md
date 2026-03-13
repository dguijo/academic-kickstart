---
# Documentation: https://sourcethemes.com/academic/docs/managing-content/

title: Studying the effect of different Lp norms in the context of Time Series Ordinal
  Classification
subtitle: ''
summary: ''
authors:
- David Guijo-Rubio
- Víctor Manuel Vargas-Yun
- Pedro Antonio Gutiérrez
- César Hervás-Martínez
tags:
- '"Lp norms"'
- '"TSOC"'
- '"time series"'
- '"L2"'
- '"L1"'
- '"ordinal classification"'
categories: []
date: '2021-09-01'
lastmod: 2021-05-24T10:30:21+02:00
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
publishDate: '2021-05-24T08:30:21.786941Z'
publication_types:
- '1'
abstract: "Time Series Ordinal Classification (TSOC) is yet an unexplored field of\
  \ machine learning consisting in the classification of time series whose labels\
  \ follow a natural order relationship between them. In this context, a well-known\
  \ approach for time series nominal classification was previously used: the Shapelet\
  \ Transform (ST). The exploitation of the ordinal information was included in two\
  \ steps of the ST algorithm: 1) by using the Pearson's determination coefficient\
  \ (R2) for computing the quality of the shapelets, which favours shapelets with\
  \ better ordering, and 2) by applying an ordinal classifier instead of a nominal\
  \ one to the transformed dataset. For this, the distance between labels was represented\
  \ by the absolute value of the difference between the corresponding ranks, i.e.\
  \ by the L1 norm. In this paper, we study the behaviour of different Lp norms for\
  \ representing class distances in ordinal regression, evaluating 9 different Lp\
  \ norms with 7 ordinal time series datasets from the UEA-UCR time series classification\
  \ repository and 10 different ordinal classifiers. The results achieved demonstrate\
  \ that the Pearson's determination coefficient using the L1.9 norm in the computation\
  \ of the difference between the shapelet and the time series labels achieves a significantly\
  \ better performance when compared to the rest of the approaches, in terms of both\
  \ Correct Classification Rate (CCR) and Average Mean Absolute Error (AMAE). "
publication: '*Proceedings of the XIX Conference of the Spanish Association for Artificial
  Intelligence (CAEPIA)*'
doi: 10.1007/978-3-030-85713-4_5
---
