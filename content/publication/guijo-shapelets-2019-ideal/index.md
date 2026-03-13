---
# Documentation: https://sourcethemes.com/academic/docs/managing-content/

title: A hybrid approach to time series classification with shapelets
subtitle: ''
summary: ''
authors:
- David Guijo-Rubio
- Pedro Antonio Gutiérrez
- R. Tavenard
- Anthony Bagnall
tags: []
categories: []
date: '2019-11-01'
lastmod: 2021-04-28T14:24:57+02:00
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
publishDate: '2021-04-28T12:24:57.059370Z'
publication_types:
- '1'
abstract: 'Shapelets are phase independent subseries that can be used to discriminate between time series. Shapelets have proved to be very effective primitives for time series classification. The two most prominent shapelet based classification algorithms are the shapelet transform (ST) and learned shapelets (LS). One significant difference between these approaches is that ST is data driven, whereas LS searches the entire shapelet space through stochastic gradient descent. The weakness of the former is that full enumeration of possible shapelets is very time consuming. The problem with the latter is that it is very dependent on the initialisation of the shapelets. We propose hybridising the two approaches through a pipeline that includes a time constrained data driven shapelet search which is then passed to a neural network architecture of learned shapelets for tuning. The tuned shapelets are extracted and formed into a transform, which is then classified with a rotation forest. We show that this hybrid approach is significantly better than either approach in isolation, and that the resulting classifier is not significantly worse than a full shapelet search.'
publication: '*Proceedings of the 20th International Conference on Intelligent Data
  Engineering and Automated Learning (IDEAL2019)*'
doi: 10.1007/978-3-030-33607-3_16
---
