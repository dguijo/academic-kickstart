---
# Documentation: https://sourcethemes.com/academic/docs/managing-content/

title: Prediction of low-visibility events due to fog using ordinal classification
subtitle: ''
summary: ''
authors:
- David Guijo-Rubio
- Pedro Antonio Gutiérrez
- Carlos Casanova-Mateo
- Julia Sanz-Justo
- Sancho Salcedo-Sanz
- César Hervás-Martínez
tags: []
categories: []
date: '2018-12-01'
lastmod: 2021-04-28T11:37:54+02:00
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
publishDate: '2021-04-28T09:37:54.140066Z'
publication_types:
- '2'
abstract: The prediction of low-visibility events is very important in many human
  activities, and crucial in transportation facilities such as airports, where they
  can cause severe impact in flight scheduling and safety. The design of accurate
  predictors for low-visibility events can be approached by modelling future visibility
  conditions based on past values of different input variables, recorded at the airport.
  The use of autoregressive time series forecasters involves adjusting the order of
  the model (number of past series values or size of the sliding window), which usually
  depends on the dynamical nature of the time series. Moreover, the same window size
  is normally used for all the data, thought it would be reasonable to use different
  sliding windows. In this paper, we propose a hybrid prediction model for daily low-visibility
  events, which combines fixed-size and dynamic windows, and adapts its size according
  to the dynamics of the time series. Moreover, visibility is labelled using three
  ordered categories (FOG, MIST and CLEAR), and the prediction is then carried out
  by means of ordinal classifiers, in order to take advantage of the ordinal nature
  of low-visibility events. We evaluate the model using a dataset from Valladolid
  airport (Spain), where radiation fog is very common in autumn and winter months.
  The considered data set includes five different meteorological input variables (wind
  speed and direction, temperature, relative humidity and QNH - pressure adjusted
  at mean sea level) and the Runway Visual Range (RVR), which is used to characterize
  the low-visibility events at the airport. The results show that the proposed hybrid
  window model with ordinal classification leads to very robust performance prediction
  in daily time-horizon, improving the results obtained by the persistence model and
  alternative prediction schemes tested.
publication: '*Atmospheric Research*'
url_pdf: doi.org/10.1016/j.atmosres.2018.07.017
doi: https://doi.org/10.1016/j.atmosres.2018.07.017
---
