---
# Documentation: https://sourcethemes.com/academic/docs/managing-content/

title: Clustering Time Series with k-Medoids Based Algorithms
subtitle: ''
summary: ''
authors:
- Christopher Holder
- David Guijo-Rubio
- Anthony Bagnall
tags: []
categories: []
date: '2023-09-01'
lastmod: 2023-12-30T09:02:27+01:00
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
publishDate: '2023-12-30T08:02:27.038732Z'
publication_types:
- '1'
abstract: 'Time Series Clustering (TSCL) involves grouping unlabelled time series
  into homogeneous groups. A popular approach to TSCL is to use the partitional clustering
  algorithms k-means or k-medoids in conjunction with an elastic distance function
  such as Dynamic Time Warping (DTW). We explore TSCL using nine different elastic
  distance measures. Both partitional algorithms characterise clusters with an exemplar
  series, but use different techniques to do so: k-means uses an averaging algorithm
  to find an exemplar, whereas k-medoids chooses a training case (medoid). Traditionally,
  the arithmetic mean of a collection of time series was used with k-means. However,
  this ignores any offset. In 2011, an averaging technique specific to DTW, called
  DTW Barycentre Averaging (DBA), was proposed. Since, k-means with DBA has been the
  algorithm of choice for the majority of partition-based TSCL and much of the research
  using medoids-based approaches for TSCL stopped. We revisit k-medoids based TSCL
  with a range of elastic distance measures. Our results show k-medoids approaches
  are significantly better than k-means on a standard test suite, independent of the
  elastic distance measure used. We also compare the most commonly used alternating
  k-medoids approach against the Partition Around Medoids (PAM) algorithm. PAM significantly
  outperforms the default k-medoids for all nine elastic measures used. Additionally,
  we evaluate six variants of PAM designed to speed up TSCL. Finally, we show PAM
  with the best elastic distance measure is significantly better than popular alternative
  TSCL algorithms, including the k-means DBA approach, and competitive with the best
  deep learning algorithms.'
publication: '*International Workshop on Advanced Analytics and Learning on Temporal
  Data*'
doi: 10.1007/978-3-031-49896-1_4
---
