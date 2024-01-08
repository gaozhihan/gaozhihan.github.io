---
title: 'PreDiff: Precipitation Nowcasting with Latent Diffusion Models'

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
  - Zhihan Gao
  - Xingjian Shi
  - Boran Han
  - Hao Wang
  - Xiaoyong Jin
  - Danielle Robinson
  - Yi Zhu
  - Mu Li
  - Yuyang Wang

# Author notes (optional)
author_notes:
  # - 'Equal contribution'
  # - 'Equal contribution'

date: '2023-07-19T00:00:00Z'
doi: ''

# Schedule page publish date (NOT publication's date).
publishDate: '2023-07-19T00:00:00Z'

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ['paper-conference']

# Publication name and optional abbreviated publication name.
publication: In 37th Conference on Neural Information Processing Systems (NeurIPS 2023)
publication_short: In NeurIPS 2023

abstract: Earth system forecasting has traditionally relied on complex physical models that are computationally expensive and require significant domain expertise. In the past decade, the unprecedented increase in spatiotemporal Earth observation data has enabled data-driven forecasting models using deep learning techniques. These models have shown promise for diverse Earth system forecasting tasks but either struggle with handling uncertainty or neglect domain-specific prior knowledge, resulting in averaging possible futures to blurred forecasts or generating physically implausible predictions. To address these limitations, we propose a *two-stage pipeline* for probabilistic spatiotemporal forecasting. 1) We develop *PreDiff*, a conditional latent diffusion model capable of probabilistic forecasts. 2) We incorporate an explicit knowledge alignment mechanism to align forecasts with domain-specific physical constraints. This is achieved by estimating the deviation from imposed constraints at each denoising step and adjusting the transition distribution accordingly. We conduct empirical studies on two datasets, *N*-body MNIST, a synthetic dataset with chaotic behavior, and SEVIR, a real-world precipitation nowcasting dataset. Specifically, we impose the law of conservation of energy in *N*-body MNIST and anticipated precipitation intensity in SEVIR. Experiments demonstrate the effectiveness of PreDiff in handling uncertainty, incorporating domain-specific prior knowledge, and generating forecasts that exhibit high operational utility. 

# Summary. An optional shortened abstract.
summary: We introduce a two-stage pipeline for probabilistic precipitation nowcasting. 1) We develop a latent diffusion model PreDiff. (2) We incorporate an auxiliary knowledge alignment mechanism, allowing the integration of domain expertise.

tags: 
- Machine Learning for Earth Science
- Precipitation Nowcasting
- Spatiotemporal Forecasting
- Generative Models
- Diffusion Models

# Display this page in the Featured widget?
featured: true

# Custom links (uncomment lines below)
# links:
# - name: Custom Link
#   url: http://example.org

url_pdf: 'https://openreview.net/pdf?id=Gh67ZZ6zkS'
url_code: 'https://github.com/gaozhihan/PreDiff'
# url_dataset: ''
url_poster: 'https://neurips.cc/media/PosterPDFs/NeurIPS%202023/72200.png'
# url_project: ''
# url_slides: ''
# url_source: ''
url_video: 'https://recorder-v3.slideslive.com/#/share?share=89506&s=2038753d-7593-4008-8aec-08ec37204769'
url_blog: 'https://www.amazon.science/blog/making-deep-learning-practical-for-earth-system-forecasting'

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder.
image:
  caption: 'L: PreDiff overview. R: extreme precipitation forecasting'
  focal_point: 'Center'
  preview_only: false

# Associated Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `internal-project` references `content/project/internal-project/index.md`.
#   Otherwise, set `projects: []`.
projects:
  - prediff

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
slides: ""
---
