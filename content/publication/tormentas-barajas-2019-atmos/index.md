---
# Documentation: https://sourcethemes.com/academic/docs/managing-content/

title: Ordinal regression algorithms for the analysis of convective situations over
  Madrid-Barajas airport
subtitle: ''
summary: ''
authors:
- David Guijo-Rubio
- Carlos Casanova-Mateo
- Juilia Sanz-Justo
- Pedro Antonio Gutiérrez
- Sara Cornejo-Bueno
- César Hervás-Martínez
- Sancho Salcedo-Sanz
tags:
- Convective clouds
- Convective analysis
- Airports
- Machine learning techniques
- Ordinal regression
categories: []
date: '2020-05-01'
lastmod: 2021-04-28T11:37:52+02:00
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
publishDate: '2021-04-28T09:37:52.411852Z'
publication_types:
- '2'
abstract: In this paper we tackle a problem of convective situations analysis at Adolfo-Suarez
  Madrid-Barajas International Airport (Spain), based on Ordinal Regression algorithms.
  The diagnosis of convective clouds is key in a large airport like Barajas, since
  these meteorological events are associated with strong winds and local precipitation,
  which may affect air and land operations at the airport. In this work, we deal with
  a 12-h time horizon in the analysis of convective clouds, using as input variables
  data from a radiosonde station and also from numerical weather models. The information
  about the objective variable (convective clouds presence at the airport) has been
  obtained from the Madrid-Barajas METAR and SPECI aeronautical reports. We treat
  the problem as an ordinal regression task, where there exist a natural order among
  the classes. Moreover, the classification problem is highly imbalanced, since there
  are very few convective clouds events compared to clear days. Thus, a process of
  oversampling is applied to the database in order to obtain a better balance of the
  samples for this specific problem. An important number of ordinal regression methods
  are then tested in the experimental part of the work, showing that the best approach
  for this problem is the SVORIM algorithm, based on the Support Vector Machine strategy,
  but adapted for ordinal regression problems. The SVORIM algorithm shows a good accuracy
  in the case of thunderstorms and Cumulonimbus clouds, which represent a real hazard
  for the airport operations.
publication: '*Atmospheric Research*'
url_pdf: doi.org/10.1016/j.atmosres.2019.104798
doi: 10.1016/j.atmosres.2019.104798
---
