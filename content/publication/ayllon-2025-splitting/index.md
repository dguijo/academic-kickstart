---
# Documentation: https://sourcethemes.com/academic/docs/managing-content/

title: 'Splitting criteria for ordinal decision trees: an experimental study'
subtitle: ''
summary: ''
authors:
- Rafael Ayllón-Gavilán
- Francisco José Martínez-Estudillo
- David Guijo-Rubio
- César Hervás-Martínez
- Pedro Antonio Gutiérrez
tags: []
categories: []
date: '2026-04-01'
lastmod: 2025-08-18T13:35:33+02:00
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
publishDate: '2025-08-18T11:35:32.953670Z'
publication_types:
- '2'
abstract: Ordinal Classification (OC) addresses those classification tasks where the
  labels exhibit a natural order. Unlike nominal classification, which treats all
  classes as mutually exclusive and unordered, OC takes the ordinal relationship into
  account, producing more accurate and relevant results. This is particularly critical
  in applications where the magnitude of classification errors has significant consequences.
  Despite this, OC problems are often tackled using nominal methods, leading to suboptimal
  solutions. Although decision trees are among the most popular classification approaches,
  ordinal tree-based approaches have received less attention when compared to other
  classifiers. This work provides a comprehensive survey of ordinal splitting criteria,
  standardising the notations used in the literature to enhance clarity and consistency.
  Three ordinal splitting criteria, Ordinal Gini (OGini), Weighted Information Gain
  (WIG), and Ranking Impurity (RI), are compared to the nominal counterparts of the
  first two (Gini and information gain), by incorporating them into a decision tree
  classifier. An extensive repository considering 45 publicly available OC datasets
  is presented, supporting the first experimental comparison of ordinal and nominal
  splitting criteria using well-known OC evaluation metrics. The results have been
  statistically analysed, highlighting that OGini stands out as the best ordinal splitting
  criterion to date, reducing the mean absolute error achieved by Gini by more than
  3.02 %. To promote reproducibility, all source code developed, a detailed guide
  for reproducing the results, the 45 OC datasets, and the individual results for
  all the evaluated methodologies are provided.
publication: '*Pattern Recognition*'
doi: 10.1016/j.patcog.2025.112273
links:
- name: URL
  url: https://www.sciencedirect.com/science/article/pii/S0031320325009343
---
