---
# Documentation: https://sourcethemes.com/academic/docs/managing-content/

title: 'O-Hydra: A Hybrid Convolutional and Dictionary-Based Approach to Time Series
  Ordinal Classification'
subtitle: ''
summary: ''
authors:
- Rafael Ayllón-Gavilán
- David Guijo-Rubio
- Pedro Antonio Gutiérrez
- César Hervás-Martı́nez
tags: []
categories: []
date: '2024-06-01'
lastmod: 2024-07-22T19:20:33+02:00
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
publishDate: '2024-07-22T17:20:33.661200Z'
publication_types:
- '1'
abstract: Time Series Ordinal Classification (TSOC) is a yet unexplored field with
  a substantial projection in following years given its applicability to numerous
  real-world problems and the possibility to obtain more consistent prediction than
  nominal Time Series Classification (TSC). Specifically, TSOC involves time series
  data along with an ordinal categorical output. That is, there is a natural order
  relationship among the labels associated with the time series. TSOC is a subfield
  of nominal TSC, with the main distinction being that TSOC exploits the ordinality
  of the labels to boost the performance. Two categories within the TSC taxonomy are
  dictionary-based and convolution-based methodologies, each representing competing
  approaches presented in the literature. In this study, we adapt the Hybrid Dictionary-Rocket
  Architecture (Hydra) approach, which incorporates elements from the two previous
  categories, to TSOC, resulting in O-Hydra. For the experiments, we have included
  a collection of 21 ordinal problems sourced from two well-known archives. O-Hydra
  has been benchmarked against its nominal counterpart, Hydra, as well as against
  two state-of-the-art approaches in the two previous categories, TDE and ROCKET,
  including their ordinal counterparts, O-TDE and O-ROCKET, respectively. The results
  achieved by the ordinal versions significantly outperformed those of current nominal
  TSC techniques. This underscores the significance of incorporating the label ordering
  when addressing such problems.
publication: '*Conference of the Spanish Association for Artificial Intelligence*'
doi: 10.1007/978-3-031-62799-6_6
links:
- name: URL
  url: https://link.springer.com/chapter/10.1007/978-3-031-62799-6_6
---
