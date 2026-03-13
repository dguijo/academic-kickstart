---
# Documentation: https://sourcethemes.com/academic/docs/managing-content/

title: Unsupervised feature based algorithms for time series extrinsic regression
subtitle: ''
summary: ''
authors:
- David Guijo-Rubio
- Matthew Middlehurst
- Guilherme Arcencio
- Diego Furtado Silva
- Anthony Bagnall
tags:
- Time series
- extrinsic regression
- unsupervised feature based algorithms
- regression
categories: []
date: '2024-05-01'
lastmod: 2024-05-20T10:58:04+02:00
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
publishDate: '2024-05-20T08:58:04.889039Z'
publication_types:
- '2'
abstract: Time Series Extrinsic Regression (TSER) involves using a set of training
  time series to form a predictive model of a continuous response variable that is
  not directly related to the regressor series. The TSER archive for comparing algorithms
  was released in 2022 with 19 problems. We increase the size of this archive to 63
  problems and reproduce the previous comparison of baseline algorithms. We then extend
  the comparison to include a wider range of standard regressors and the latest versions
  of TSER models used in the previous study. We show that none of the previously evaluated
  regressors can outperform a regression adaptation of a standard classifier, rotation
  forest. We introduce two new TSER algorithms developed from related work in time
  series classification. FreshPRINCE is a pipeline estimator consisting of a transform
  into a wide range of summary features followed by a rotation forest regressor. DrCIF
  is a tree ensemble that creates features from summary statistics over random intervals.
  Our study demonstrates that both algorithms, along with InceptionTime, exhibit significantly
  better performance compared to the other 18 regressors tested. More importantly,
  DrCIF is the only one that significantly outperforms a standard rotation forest
  regressor.
publication: '*Data Mining and Knowledge Discovery*'
doi: 10.1007/s10618-024-01027-w
links:
- name: URL
  url: https://link.springer.com/article/10.1007/s10618-024-01027-w
---
