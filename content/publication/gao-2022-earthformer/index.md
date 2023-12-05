---
title: 'Earthformer: Exploring Space-Time Transformers for Earth System Forecasting'

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
  - Zhihan Gao
  - Xingjian Shi
  - Hao Wang
  - Yi Zhu
  - Yuyang Wang
  - Mu Li
  - Dit-Yan Yeung

# Author notes (optional)
author_notes:
  # - 'Equal contribution'
  # - 'Equal contribution'

date: '2022-12-06T00:00:00Z'
doi: ''

# Schedule page publish date (NOT publication's date).
publishDate: '2022-12-06T00:00:00Z'

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ['paper-conference']

# Publication name and optional abbreviated publication name.
publication: In 36th Conference on Neural Information Processing Systems (NeurIPS 2022)
publication_short: In NeurIPS 2022

abstract: Conventionally, Earth system (e.g., weather and climate) forecasting relies on numerical simulation with complex physical models and hence is both expensive in computation and demanding on domain expertise. With the explosive growth of spatiotemporal Earth observation data in the past decade, data-driven models that apply Deep Learning (DL) are demonstrating impressive potential for various Earth system forecasting tasks. The Transformer as an emerging DL architecture, despite its broad success in other domains, has limited adoption in this area. In this paper, we propose Earthformer, a space-time Transformer for Earth system forecasting. Earthformer is based on a generic, flexible and efficient space-time attention block, named Cuboid Attention. The idea is to decompose the data into cuboids and apply cuboid-level self-attention in parallel. These cuboids are further connected with a collection of global vectors. We conduct experiments on the MovingMNIST dataset and a newly proposed chaotic *N*-body MNIST dataset to verify the effectiveness of cuboid attention and figure out the best design of Earthformer. Experiments on two real-world benchmarks about precipitation nowcasting and El Niño/Southern Oscillation (ENSO) forecasting show that Earthformer achieves state-of-the-art performance. 

# Summary. An optional shortened abstract.
summary: We propose Earthformer with novel generic building blocks "Cuboid Attention" to explore the design of space-time attention for Earth system forecasting problems, and achieve SOTA performance on two synthetic datasets and two real-world benchmarks.

tags: 
- Machine Learning for Earth Science
- Precipitation Nowcasting
- Spatiotemporal Forecasting
- Transformers

# Display this page in the Featured widget?
featured: true

# Custom links (uncomment lines below)
# links:
# - name: Custom Link
#   url: http://example.org

url_pdf: 'https://openreview.net/pdf?id=lzZstLVGVGW'
url_code: 'https://github.com/amazon-research/earth-forecasting-transformer'
# url_dataset: ''
url_poster: 'https://earthformer.s3.amazonaws.com/docs/Earthformer_poster_NeurIPS22.pdf'
# url_project: ''
# url_slides: ''
# url_source: ''
url_video: 'https://slideslive.com/38995604/earthformer-exploring-spacetime-transformers-for-earth-system-forecasting'

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder.
image:
  caption: 'Illustration of cuboid decomposition strategies.'
  focal_point: 'Center'
  preview_only: false

# Associated Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `internal-project` references `content/project/internal-project/index.md`.
#   Otherwise, set `projects: []`.
projects:
  - earthformer

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
slides: ""
---
