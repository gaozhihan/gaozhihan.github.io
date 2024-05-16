---
title: 'Probabilistic Continuous-Time Whole-Graph Forecasting'

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
- ZhihanGao
- Hao Wang
- Yuyang Wang
- Xingjian Shi
- Dit-Yan Yeung

# Author notes (optional)
author_notes:
  # - 'Equal contribution'
  # - 'Equal contribution'

date: '2022-08-15T00:00:00Z'
doi: ''

# Schedule page publish date (NOT publication's date).
publishDate: '2022-08-15T00:00:00Z'

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ['paper-conference']

# Publication name and optional abbreviated publication name.
publication: 'SIGKDD International Workshop on Mining and Learning from Time Series -- Deep Forecasting: Models, Interpretability, and Applications'
publication_short: SIGKDD-MiLeTS 2022

abstract: Dynamic graph forecasting has found a wide range of applications including social media, recommendation systems, and computational finance. However, existing dynamic graph models typically focus on discrete-time dynamic graphs, treating dynamic graphs as temporally discrete graph snapshots. We argue that such discrete treatment is inadequate for capturing the underlying dynamics which are intrinsically continuous. To overcome such deficiency, we extend fully connected neural ordinary differential equations (FCNODE) to graph-connected neural ordinary differential equations (GNODE), which considers graph structures in the input space, output space, and the transition in the latent space. Experiments show that our GNODE naturally captures the continuous-time dynamics in graph sequences and consistently outperforms state-of-the-art graph forecasting methods.

# Summary. An optional shortened abstract.
# summary: ""

tags: 
- Graph
- Neural ODEs

# Display this page in the Featured widget?
featured: false

# Custom links (uncomment lines below)
# links:
# - name: Custom Link
#   url: http://example.org

url_pdf: 'https://kdd-milets.github.io/milets2022/papers/MILETS_2022_paper_7178.pdf'
# url_code: ''
# url_dataset: ''
# url_poster: 'https://earthformer.s3.amazonaws.com/docs/Earthformer_poster_NeurIPS22.pdf'
# url_project: ''
# url_slides: ''
# url_source: ''
# url_video: 'https://slideslive.com/38995604/earthformer-exploring-spacetime-transformers-for-earth-system-forecasting'

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder.
image:
  caption: 'Overview of GNODE.'
  focal_point: 'Center'
  preview_only: false

# Associated Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `internal-project` references `content/project/internal-project/index.md`.
#   Otherwise, set `projects: []`.
projects: []

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
slides: ""
---

