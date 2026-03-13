---
# Documentation: https://sourcethemes.com/academic/docs/managing-content/

title: An Evolutionary Artificial Neural Network approach for spatio-temporal wave
  height time series reconstruction
subtitle: ''
summary: ''
authors:
- David Guijo-Rubio
- Antonio M. Durán-Rosal
- Antonio M. Gómez-Orellana
- Juan C. Fernández
tags:
- Time series reconstruction
- Marine engineering
- Wave height reconstruction
- Evolutionary Artificial Neural Networks
- Ocean buoys
categories: []
date: '2023-10-01'
lastmod: 2023-08-04T11:08:34+02:00
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
publishDate: '2023-08-04T09:08:34.352483Z'
publication_types:
- '2'
abstract: 'This paper proposes a novel methodology for recovering missing time series
  data, a crucial task for subsequent Machine Learning (ML) analyses. The methodology
  is specifically applied to Significant Wave Height (SWH) time series in the field
  of marine engineering. The proposed approach involves two phases. Firstly, the SWH
  time series for each buoy is independently reconstructed using three transfer function
  models: regression-based, correlation-based, and distance-based. The distance-based
  transfer function exhibits the best overall performance. Secondly, Evolutionary
  Artificial Neural Networks (EANNs) are utilised for the final recovery of each time
  series, using as inputs highly correlated buoys that have been intermediately recovered.
  The EANNs are evolved considering two metrics, the novel squared error relevance
  area, which balances the importance of extreme and around-mean values, and the well-known
  mean squared error. The study considers SWH time series data from 15 buoys in two
  coastal zones in the United States. The results demonstrate that the distance-based
  transfer function is generally the best transfer function, and that EANNs outperform
  a range of state-of-the-art ML techniques in 12 out of the 15 buoys, with a number
  of connections comparable to linear models. Furthermore, the proposed methodology
  outperforms the two most popular approaches for time series reconstruction, BRITS
  and SAITS, for all buoys except one. Therefore, the proposed methodology provides
  a promising approach, which may be applied to time series from other fields, such
  as wind or solar energy farms in the field of green energy.'
publication: '*Applied Soft Computing*'
doi: 10.1016/j.asoc.2023.110647
links:
- name: URL
  url: https://www.sciencedirect.com/science/article/pii/S1568494623006658
---
