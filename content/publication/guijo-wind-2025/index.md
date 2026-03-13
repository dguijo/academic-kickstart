---
# Documentation: https://sourcethemes.com/academic/docs/managing-content/

title: 'Wind speed prediction using ordinal classification: an analysis of extreme
  values'
subtitle: ''
summary: ''
authors:
- David Guijo-Rubio
- Antonio M. Gómez-Orellana
- Víctor M. Vargas
- Rafael Ayllón-Gavilán
- Laura Cornejo-Bueno
- Francisco Moreno-Cano
- César Hervás-Martínez
- Sancho Salcedo-Sanz
- Pedro A. Gutiérrez
tags: []
categories: []
date: '2025-05-01'
lastmod: 2025-08-18T14:02:11+02:00
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
publishDate: '2025-08-18T12:02:11.648817Z'
publication_types:
- '1'
abstract: 'Wind speed forecasting represents a significant challenge in the global
  transition to sustainable energy systems. Wind energy, characterised by zero greenhouse
  gas emissions and relatively low cost, is a renewable resource that depends heavily
  on meteorological conditions, which are inherently variable and unpredictable. This
  variability and intermittency present substantial obstacles to ensuring a consistent
  power supply, underscoring the importance of accurate wind speed prediction as a
  critical area of research. Among the various approaches explored to address this
  challenge, machine learning (ML) has emerged as a prominent solution. ML includes
  methodologies such as regression (predicting continuous values of wind speed) and
  nominal classification (predicting discrete categories of wind speed). In nominal
  classification, wind speeds are discretised into classes to provide essential information
  for wind farm operations. In this study, wind speeds are categorised into four classes:
  1) very low speeds, 2) moderate speeds, 3) high speeds, and 4) extreme wind speeds.
  While both very low and extreme speeds result in no power generation, this work
  focuses on the extreme wind speed class, as these events often necessitate turbine
  shutdowns to prevent structural damage. To address the challenges of wind speed
  forecasting with a focus on extreme wind events, we propose the use of ordinal classification,
  a ML paradigm specifically designed for tasks where output categories exhibit a
  natural order, as is the case in this work. This study evaluates hourly wind speed
  predictions for a wind farm in Spain, using data collected over more than 15 years.
  Additionally, input features include meteorological variables such as temperature,
  wind components (u and v), and sea level pressure, among others. Forecasts are generated
  for three time horizons (1h, 4h, and 8h) to provide sufficient lead time for mitigating
  risks associated with extreme wind conditions. Two ordinal classification models
  based on artificial neural networks (ANNs) are analysed: 1) an ANN coupled with
  the cumulative link model (CLM), and 2) an ANN using a soft labelling optimisation
  technique. Additionally, other competitive ordinal and nominal classification methods
  are included for comparative analysis. The results demonstrate that the proposed
  models outperform a number of nominal and ordinal classification methods. The ANN
  coupled with CLM delivers superior overall performance across all four classes,
  while the ANN employing the soft labelling approach achieves higher accuracy in
  predicting extreme wind speed events. These findings underscore the potential of
  ordinal classification to enhance wind speed forecasting, contributing to more effective
  wind farm management and the broader integration of renewable energy sources.'
publication: '*EGU General Assembly 2025*'
doi: 10.5194/egusphere-egu25-15414
links:
- name: URL
  url: https://meetingorganizer.copernicus.org/EGU25/EGU25-15414.html
---
