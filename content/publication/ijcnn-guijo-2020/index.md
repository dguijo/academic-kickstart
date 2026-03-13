---
# Documentation: https://sourcethemes.com/academic/docs/managing-content/

title: Time series ordinal classification via shapelets
subtitle: ''
summary: ''
authors:
- David Guijo-Rubio
- Pedro Antonio Gutiérrez
- Anthony Bagnall
- César Hervás-Martínez
tags: []
categories: []
date: '2020-07-01'
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
publishDate: '2021-04-28T12:24:56.534319Z'
publication_types:
- '1'
abstract: 'Nominal time series classification has been widely
developed over the last years. However, to the best of our
knowledge, ordinal classification of time series is an unexplored
field, and this paper proposes a first approach in the context of
the shapelet transform (ST). For those time series dataset where
there is a natural order between the labels and the number
of classes is higher than 2, nominal classifiers are not capable
of achieving the best results, because the models impose the
same cost of misclassification to all the errors, regardless the
difference between the predicted and the ground-truth. In this
sense, we consider four different evaluation metrics to do so,
three of them of an ordinal nature. The first one is the widely
known Information Gain (IG), proved to be very competitive
for ST methods, whereas the remaining three measures try to
boost the order information by refining the quality measure.
These three measures are a reformulation of the Fisher score, the
Spearman’s correlation coefficient (ρ), and finally, the Pearson’s
correlation coefficient (R²). An empirical evaluation is carried
out, considering 7 ordinal datasets from the UEA & UCR
time series classification repository, 4 classifiers (2 of them of
nominal nature, whereas the other 2 are of ordinal nature) and
2 performance measures (correct classification rate, CCR, and
average mean absolute error, AMAE). The results show that,
for both performance metrics, the ST quality metric based on
R² is able to obtain the best results, specially for AMAE, for
which the differences are statistically significant in favour of R².'
publication: '*Proceedings of the 2020  IEEE International Joint Conference on Neural
  Networks (IJCNN2020)*'
doi: 10.1109/IJCNN48605.2020.9207200
---
