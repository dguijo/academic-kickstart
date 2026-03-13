---
# Documentation: https://sourcethemes.com/academic/docs/managing-content/

title: Energy Flux Prediction Using an Ordinal Soft Labelling Strategy
subtitle: ''
summary: ''
authors:
- Antonio M Gómez-Orellana
- Vı́ctor M Vargas
- Pedro A Gutiérrez
- Jorge Pérez-Aracil
- Sancho Salcedo-Sanz
- César Hervás-Mart\ńez
- David Guijo-Rubio
tags: []
categories: []
date: '2024-06-01'
lastmod: 2024-07-22T18:55:10+02:00
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
publishDate: '2024-07-22T16:55:09.682325Z'
publication_types:
- '1'
abstract: This paper addresses the problem of short-term energy flux prediction. For
  this purpose, we propose the use of an ordinal classification neural network model
  optimised using the triangular regularised categorical cross-entropy loss, termed
  MLP-T. This model is based on a soft labelling strategy, that replaces the crisp
  0/1 labels on the loss computation with soft versions encoding the ordinal information.
  This soft label encoding leverages the inherent ordering between categories to reduce
  the cost of ordinal classification errors and improve model generalisation performance.
  Specifically, the soft labels for each target class are derived from triangular
  probability distributions. To assess the performance of MLP-T, six datasets built
  from buoy measurements and reanalysis data have been used. MLP-T has been compared
  to nominal and ordinal classification techniques in terms of four performance metrics.
  MLP-T achieved an outstanding performance across all datasets and performance metrics,
  securing the best mean results. Despite the imbalanced nature of the problem, which
  makes the ordinal classification task notably difficult, MLP-T achieved good results
  in all classes across all datasets, including the underrepresented classes. Remarkably,
  MLP-T was the only approach that correctly classified at least one instance of the
  minority class in all datasets. Furthermore, MLP-T secured the top rank in all cases,
  confirming its suitability for the problem addressed.
publication: '*International Work-Conference on the Interplay Between Natural and
  Artificial Computation*'
doi: 10.1007/978-3-031-61137-7_26
links:
- name: URL
  url: https://link.springer.com/chapter/10.1007/978-3-031-61137-7_26
---
