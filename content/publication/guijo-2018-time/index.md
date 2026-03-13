---
# Documentation: https://sourcethemes.com/academic/docs/managing-content/

title: Time series clustering based on the characterisation of segment typologies
subtitle: ''
summary: ''
authors:
- David Guijo-Rubio
- Antonio Manuel Durán-Rosal
- Pedro Antonio Gutiérrez
- Alicia Troncoso
- César Hervás-Martínez
tags: []
categories: []
date: '2018-11-01'
lastmod: 2021-04-28T14:15:46+02:00
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
publishDate: '2021-04-28T12:15:46.406357Z'
publication_types:
- '1'
abstract: Time series clustering is the process of grouping time series with respect
  to their similarity or characteristics. Previous approaches usually combine a specific
  distance measure for time series and a standard clustering method. However, these
  approaches do not take the similarity of the different subsequences of each time
  series into account, which can be used to better compare the time series objects
  of the dataset. In this paper, we propose a novel technique of time series clustering
  based on two clustering stages. In a first step, a least squares polynomial segmentation
  procedure is applied to each time series, which is based on a growing window technique
  that returns different-length segments. Then, all the segments are projected into
  same dimensional space, based on the coefficients of the model that approximates
  the segment and a set of statistical features. After mapping, a first hierarchical
  clustering phase is applied to all mapped segments, returning groups of segments
  for each time series. These clusters are used to represent all time series in the
  same dimensional space, after defining another specific mapping process. In a second
  and final clustering stage, all the time series objects are grouped. We consider
  internal clustering quality to automatically adjust the main parameter of the algorithm,
  which is an error threshold for the segmentation. The results obtained on 84 datasets
  from the UCR Time Series Classification Archive have been compared against two state-of-the-art
  methods, showing that the performance of this methodology is very promising.
publication: '*Proceedings of Third Bilbao Data Science Workshop (BiDAS 3)*'
---
