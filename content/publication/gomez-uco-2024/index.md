---
title: Predicción a corto plazo de la energía undimotriz mediante un enfoque ordinal
  de etiquetado suave

# Authors
# A YAML list of author names
# If you created a profile for a user (e.g. the default `admin` user at `content/authors/admin/`), 
# write the username (folder name) here, and it will be replaced with their full name and linked to their profile.
authors:
- Antonio Manuel Gómez-Orellana
- David Guijo-Rubio
- Pedro Antonio Gutiérrez

# Author notes (such as 'Equal Contribution')
# A YAML list of notes for each author in the above `authors` list
author_notes: []

date: '2024-05-01'

# Date to publish webpage (NOT necessarily Bibtex publication's date).
publishDate: '2025-02-11T11:35:26.332936Z'

# Publication type.
# A single CSL publication type but formatted as a YAML list (for Hugo requirements).
publication_types:
- '6'

# Publication name and optional abbreviated publication name.
publication: '*XII Congreso Cientı́fico de Investigadores en Formación*'
publication_short: ''

doi: ''

abstract: 'In this study, the problem of short-term prediction of wave energy is approached from an ordinal
perspective. For this purpose, we propose the use of a soft labeling approach, which replaces the
0/1 encoding of the classes with soft labels. Specifically, such soft labels or probabilities are
obtained from triangular probability distributions, which better distribute the probabilities: the
target class receives higher probability than its adjacents classes. Therefore, integrating the soft
labeling approach into the loss function modifies the computation of the error during model
optimization, now taking into account the ordinal information encoded in the soft labels. For this
purpose, an ordinal classification artificial neural network model, termed RNA-T, is implemented
and optimized using a categorical cross-entropy loss function that integrates the proposed soft
labeling approach. The performance of the RNA-T model is analyzed using two datasets built
from reanalysis data and measurements recorded by marine buoys. The RNA-T model is
compared, in terms of two ordinal performance metrics, with two standard ordinal classification
techniques. The results confirm the superiority of the RNA-T model over the compared
techniques.'

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
---