---
title: Hybrid Dropout for Deep Ordinal Classification

# Authors
# A YAML list of author names
# If you created a profile for a user (e.g. the default `admin` user at `content/authors/admin/`), 
# write the username (folder name) here, and it will be replaced with their full name and linked to their profile.
authors:
- Francisco Bérchez-Moreno
- Francisco Moreno-Cano
- David Guijo-Rubio
- Víctor M. Vargas
- Pedro A. Gutiérrez
- César Hervás-Martínez

# Author notes (such as 'Equal Contribution')
# A YAML list of notes for each author in the above `authors` list
author_notes: []

date: '2025-06-01'

# Date to publish webpage (NOT necessarily Bibtex publication's date).
publishDate: '2025-10-01T08:23:13.755811Z'

# Publication type.
# A single CSL publication type but formatted as a YAML list (for Hugo requirements).
publication_types:
- '1'

# Publication name and optional abbreviated publication name.
publication: '*International Work-Conference on Artificial Neural Networks*'
publication_short: ''

doi: 10.1007/978-3-032-02725-2_39

abstract: This paper presents a new application of a hybrid dropout technique for
  Ordinal Classification (OC), based on a novel regularisation method. Unlike standard
  dropout, which ignores class ordering, this hybrid dropout integrates ordinal information
  by adjusting neurons dropout probabilities based on their correlation with target
  labels. We evaluate its effectiveness using a ResNet18 architecture over three new
  OC datasets and compare it with the standard dropout approach and with an architecture
  with no dropout. Results show that the hybrid dropout consistently achieves the
  best performance across multiple well-known metrics (1-off, QWK, MAE, AMAE, and
  RPS), while also reducing prediction variability. Statistical analysis using the
  Wilcoxon signed-rank test confirms its robustness, obtaining 21 significant wins
  out of 30 comparisons, with no losses. These results highlight the importance of
  designing regularisation strategies that consider the problems ordinal structure,
  demonstrating that hybrid dropout effectively enhances generalisation and predictive
  accuracy.

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
  url: https://link.springer.com/'6'/10.1007/978-3-032-02725-2_39
---


