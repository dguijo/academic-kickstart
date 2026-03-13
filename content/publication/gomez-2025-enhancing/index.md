---
title: Enhancing wind speed prediction in wind farms through ordinal classification

# Authors
# A YAML list of author names
# If you created a profile for a user (e.g. the default `admin` user at `content/authors/admin/`), 
# write the username (folder name) here, and it will be replaced with their full name and linked to their profile.
authors:
- Antonio Manuel Gómez-Orellana
- Marta Vega-Bayo
- David Guijo-Rubio
- Jorge Pérez-Aracil
- Víctor Manuel Vargas
- Pedro Antonio Gutiérrez
- Luis Prieto-Godino
- Sancho Salcedo-Sanz
- César Hervás-Martínez

# Author notes (such as 'Equal Contribution')
# A YAML list of notes for each author in the above `authors` list
author_notes: []

date: '2025-12-01'

# Date to publish webpage (NOT necessarily Bibtex publication's date).
publishDate: '2025-10-01T07:57:56.953573Z'

# Publication type.
# A single CSL publication type but formatted as a YAML list (for Hugo requirements).
publication_types:
- '2'

# Publication name and optional abbreviated publication name.
publication: '*Energy and AI*'
publication_short: ''

doi: 10.1016/j.egyai.2025.100596

abstract: 'This paper presents and evaluates two novel ordinal classification methods
  for wind speed prediction, considering three prediction time-horizons: 1h, 4h, and
  8h. To address the problem, wind speed values are discretised into four classes,
  critical for wind farm management. Each class represents essential information for
  wind farm production, ranging from very low wind speeds to extreme wind speed events
  and the corresponding production conditions, facilitating operational decisions
  for wind farm operators. Ordinal classifiers are more suitable than nominal methods
  to tackle this problem. The study’s primary objective is to compare recently proposed
  ordinal classifiers for addressing the challenges of wind speed prediction with
  a focus on extreme wind conditions, which are responsible for many turbine shutdowns.
  Hourly wind speed measurements from a Spanish wind farm and predictor variables
  from the European Centre for Medium-Range Weather Forecasts Reanalysis v5 (ERA5
  Reanalysis) model are used. The proposed methods include an Artificial Neural Network
  (ANN) model implementing the Cumulative Link Model as an ordinal output function
  (MLP-CLMO), which emphasises overall performance, and an ANN model optimised using
  a soft labelling technique based on triangular distributions (MLP-TO), which excels
  at handling extreme class performance. The results demonstrate the superiority of
  both approaches over other nominal and ordinal methods across performance metrics
  that account for the unbalanced nature and ordinality of the data. MLP-CLMO excels
  in overall and ordinal performance, while MLP-TO demonstrates superior handling
  of the extreme class predictions.'

# Summary. An optional shortened abstract.
summary: ''

tags: []

# Display this page in a list of Featured pages?
featured: false

# Links
url_pdf: ''
url_code: ''
url_dataset: ''
url_poster: ''
url_project: ''
url_slides: ''
url_source: ''
url_video: ''

# Custom links (uncomment lines below)
# links:
# - name: Custom Link
#   url: http://example.org

# Publication image
# Add an image named `featured.jpg/png` to your page's folder then add a caption below.
image:
  caption: ''
  focal_point: ''
  preview_only: false

# Associated Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `projects: ['internal-project']` links to `content/project/internal-project/index.md`.
#   Otherwise, set `projects: []`.
projects: []
links:
- name: URL
  url: https://www.sciencedirect.com/science/article/pii/S2666546825001284
---


