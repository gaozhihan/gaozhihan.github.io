---
title: 'Multi-Modal Learning for Geospatial Vegetation Forecasting'

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
  - Vitus Benson
  - Claire Robin
  - Christian Requena-Mesa
  - Lazaro Alonso
  - Nuno Carvalhais
  - José Cortés
  - Zhihan Gao
  - Nora Linscheid
  - Mélanie Weynants
  - Markus Reichstein

# Author notes (optional)
author_notes:
  # - 'Equal contribution'
  # - 'Equal contribution'

date: '2024-03-07T00:00:00Z'
doi: ''

# Schedule page publish date (NOT publication's date).
publishDate: '2024-03-07T00:00:00Z'

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ['paper-conference']

# Publication name and optional abbreviated publication name.
publication: In the IEEE/CVF Conference on Computer Vision and Pattern Recognition 2024 (CVPR 2024)
publication_short: In CVPR 2024

abstract: The innovative application of precise geospatial vegetation forecasting holds immense potential across diverse sectors, including agriculture, forestry, humanitarian aid, and carbon accounting. To leverage the vast availability of satellite imagery for this task, various works have applied deep neural networks for predicting multispectral images in photorealistic quality. However, the important area of vegetation dynamics has not been thoroughly explored. Our study breaks new ground by introducing GreenEarthNet, the first dataset specifically designed for high-resolution vegetation forecasting, and Contextformer, a novel deep learning approach for predicting vegetation greenness from Sentinel 2 satellite images with fine resolution across Europe. Our multi-modal transformer model Contextformer leverages spatial context through a vision backbone and predicts the temporal dynamics on local context patches incorporating meteorological time series in a parameterefficient manner. The GreenEarthNet dataset features a learned cloud mask and an appropriate evaluation scheme for vegetation modeling. It also maintains compatibility with the existing satellite imagery forecasting dataset EarthNet2021, enabling cross-dataset model comparisons. Our extensive qualitative and quantitative analyses reveal that our methods outperform a broad range of baseline stechniques. This includes surpassing previous state-of-theart models on EarthNet2021, as well as adapted models from time series forecasting and video prediction. To the best of our knowledge, this work presents the first models for continental-scale vegetation modeling at fine resolution able to capture anomalies beyond the seasonal cycle, thereby paving the way for predicting vegetation health and behaviour in response to climate variability and extremes. We provide open source code and pre-trained weights to reproduce our experimental results under https://github.com/vitusbenson/greenearthnet.

# Summary. An optional shortened abstract.
summary: 'We benchmark a wide range of EarthNet models on the new GreenEarthNet dataset, plus introducing a new transformer-based SOTA: Contextformer.'

tags: 
- Machine Learning for Earth Science
- Spatiotemporal Forecasting
- Transformers
- Dataset

# Display this page in the Featured widget?
featured: false

# Custom links (uncomment lines below)
# links:
# - name: Custom Link
#   url: http://example.org

url_pdf: 'https://arxiv.org/pdf/2303.16198v2'
url_code: 'https://github.com/vitusbenson/greenearthnet'
url_dataset: 'https://www.earthnet.tech'
# url_poster: ''
# url_project: ''
# url_slides: ''
# url_source: ''
# url_video: ''
# url_blog: ''

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder.
# image:
#   caption: ''
#   focal_point: 'Center'
#   preview_only: false

# Associated Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `internal-project` references `content/project/internal-project/index.md`.
#   Otherwise, set `projects: []`.
projects:
  - earthnet

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
slides: ""
---
