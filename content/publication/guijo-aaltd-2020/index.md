---
# Documentation: https://sourcethemes.com/academic/docs/managing-content/

title: Ordinal versus nominal time series classification
subtitle: ''
summary: ''
authors:
- David Guijo-Rubio
- Pedro Antonio Gutiérrez
- Anthony Bagnall
- César Hervás-Martínez
tags: []
categories: []
date: '2020-09-01'
lastmod: 2021-04-28T14:24:56+02:00
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
publishDate: '2021-04-28T12:24:56.329661Z'
publication_types:
- '1'
abstract: 'Time series ordinal classification is one of the less studied problems in time series data mining. This problem consists in classifying time series with labels that show a natural order between them. In this paper, an approach is proposed based on the Shapelet Transform (ST) specifically adapted to ordinal classification. ST consists of two different steps: 1) the shapelet extraction procedure and its evaluation; and 2) the classifier learning using the transformed dataset. In this way, regarding the first step, 3 ordinal shapelet quality measures are proposed to assess the shapelets extracted, and, for the second step, an ordinal classifier is applied once the transformed dataset has been constructed. An empirical evaluation is carried out, considering 7 ordinal datasets from the UEA & UCR Time Series Classification (TSC) repository. The results show that a support vector ordinal classifier applied to the ST using the Pearson’s correlation coefficient (R2) is the combination achieving the best resultsin terms of two evaluation metrics: accuracy and average mean absolute error. A final comparison against three of the most popular and compet-itive nominal TSC techniques is performed, demonstrating that ordinal approaches can achieve higher performances even in terms of accuracy.'
publication: '*Proceedings of the 5th Workshop on Advances Analytics and Learning
 on Temporal Data*'
doi: 10.1007/978-3-030-65742-0_2
url_pdf: https://project.inria.fr/aaltd20/files/2020/08/AALTD_20_paper_Guijo-Rubio.pdf
---
