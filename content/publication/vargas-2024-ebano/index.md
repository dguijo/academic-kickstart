---
# Documentation: https://sourcethemes.com/academic/docs/managing-content/

title: 'EBANO: A novel Ensemble BAsed on uNimodal Ordinal classifiers for the prediction
  of significant wave height'
subtitle: ''
summary: ''
authors:
- Víctor M Vargas
- Antonio M Gómez-Orellana
- Pedro A Gutiérrez
- César Hervás-Martínez
- David Guijo-Rubio
tags: []
categories: []
date: '2024-09-01'
lastmod: 2024-07-22T19:14:19+02:00
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
publishDate: '2024-07-22T17:14:19.415992Z'
publication_types:
- '2'
abstract: In this study, we present EBANO (Ensemble BAsed on uNimodal Ordinal classifiers),
  which is a novel ensemble approach of ordinal classifiers that includes four soft
  labelling approaches along with an ordinal logistic regression model. These models
  are integrated within the ensemble using a new aggregation methodology that automatically
  weights each individual classifier using a randomised search algorithm. In addition,
  the proposed EBANO methodology is applied to tackle short-term prediction of Significant
  Wave Height (SWH). Thus, we employ EBANO using a diverse set of eight datasets derived
  from reanalysis data and buoy-recorded SWH measurements. To approach the problem
  from an ordinal classification perspective, the SWH values are discretised into
  five ordered classes by applying hierarchical clustering. EBANO is compared with
  each of the individual classifiers integrated in the proposed ensemble along with
  a different ensemble technique termed HESCA. Both the average results and the ranks
  obtained show the superiority of EBANO over the compared methodologies, being more
  pronounced in the metrics that account for the imbalance present in the datasets
  considered. Finally, a statistical analysis is performed, confirming the statistical
  significance of the observed differences in all comparisons. This analysis underscores
  the effectiveness of EBANO in addressing the problem of SWH prediction, showcasing
  its excellence.
publication: '*Knowledge-Based Systems*'
doi: 10.1016/j.knosys.2024.112223
links:
- name: URL
  url: https://www.sciencedirect.com/science/article/pii/S0950705124008578
---
