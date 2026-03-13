---
# Documentation: https://sourcethemes.com/academic/docs/managing-content/

title: Clustering de Series Temporales basado en la Extracción de Tipologías de Segmentos
subtitle: ''
summary: ''
authors:
- David Guijo-Rubio
- Antonio Manuel Durán-Rosal
- Pedro Antonio Gutiérrez
- César Hervás-Martínez
tags:
- Time series clustering
- time series segmentation
- ''
categories: []
date: '2016-11-01'
lastmod: 2021-04-28T14:24:58+02:00
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
publishDate: '2021-04-28T12:24:58.465451Z'
publication_types:
- '6'
abstract: Durante los últimos años se ha producido un gran aumento de series de datos
  distribuidas a lo largo del tiempo, o lo que es lo mismo, de series temporales.
  Este crecimiento ha traído consigo un interés en su agrupamiento o clustering, proceso
  de agrupar las series de forma que, las series de un mismo grupo sean muy similares
  entre sí y muy diferentes a las de otros grupos. Cuando las series temporales son
  muy largas, presentan ruido o valores perdidos, muchos de los métodos actuales obtienen
  soluciones que no son aceptables. En este artículo se presenta un nuevo método de
  clustering para series temporales, mediante polinomios utilizando un método conocido
  como Growing Window. De esta forma simplificamos la serie a un conjunto de coeficientes
  lineales de grado variable, para, posteriormente, agrupar los diferentes segmentos
  y hallar los centroides de cada cluster. Al final la serie queda simplificada a
  n x d elementos, siendo n el número de clusters y d el grado del polinomio utilizado
  en la aproximación y es con esta representación con la que se realiza la agrupación
  final. El objetivo de esta nueva metodología consiste en disminuir la dimensionalidad
  de la serie temporal, la sensibilidad del agrupamiento y los datos perdidos.
publication: '*Actas del I Congreso de Investigadores Noveles de la Universidad de
  Córdoba*'
---
