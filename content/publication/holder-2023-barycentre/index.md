---
# Documentation: https://sourcethemes.com/academic/docs/managing-content/

title: Barycentre Averaging for the Move-Split-Merge Time Series Distance Measure
subtitle: ''
summary: ''
authors:
- Christopher Holder
- David Guijo-Rubio
- Anthony Bagnall
tags: []
categories: []
date: '2023-11-01'
lastmod: 2023-12-30T09:05:52+01:00
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
publishDate: '2023-12-30T08:05:51.958191Z'
publication_types:
- '1'
abstract: Distance functions play a core role in many time series machine learning
  algorithms for tasks such as clustering, classification and regression. Time series
  often require bespoke distance functions because small offsets in time can lead
  to large distances between series that are conceptually similar. Elastic distances
  compensate for misalignment by creating a path through a cost matrix by warping
  and/or editing time series. Time series are most commonly clustered with partitional
  algorithms such as k-means and k-medoids using elastic distance measures such as
  Dynamic Time Warping (DTW). The distance is used to assign cases to the closest
  cluster representative. k-means requires the averaging of time series to find these
  representative centroids. If DTW is used to assign membership, but the arithmetic
  mean is used to find centroids, k-means performance degrades significantly. An averaging
  technique specific to DTW, called DTW Barycentre Averaging (DBA), overcomes the
  averaging problem. However, can only be used with DTW. As such alternative distance
  functions such as Move-Split-Merge (MSM) are forced to use the arithmetic mean to
  compute new centroids and suffer similar degraded performance as k-means-DTW without
  DBA. To address this we propose a averaging method for MSM distance, MSM Barycentre
  Averaging (MBA) and show that when used to find centroids it significantly improves
  MSM based k-means and is better than commonly used alternatives
publication: '*Proceedings of the 15th International Joint Conference on Knowledge
  Discovery, Knowledge Engineering and Knowledge Management - KDIR*'
doi: 10.5220/0012164900003598
---
