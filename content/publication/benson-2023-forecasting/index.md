---
title: "Forecasting Localized Weather Impacts on Vegetation as Seen from Space with Meteo-Guided Video Prediction"
authors:
- Vitus Benson
- Christian Requena-Mesa
- Claire Robin
- Lazaro Alonso
- José Cortés
- Zhihan Gao
- Nora Linscheid
- Mélanie Weynants
- Markus Reichstein
date: "2023-03-28T00:00:00Z"
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: "2023-03-28T00:00:00Z"

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ["article"]

# Publication name and optional abbreviated publication name.
publication: "*arXiv preprint arXiv:2303.16198*"
publication_short: ""

abstract: We present a novel approach for modeling vegetation response to weather in Europe as measured by the Sentinel 2 satellite. Existing satellite imagery forecasting approaches focus on photorealistic quality of the multispectral images, while derived vegetation dynamics have not yet received as much attention. We leverage both spatial and temporal context by extending state-of-the-art video prediction methods with weather guidance. We extend the EarthNet2021 dataset to be suitable for vegetation modeling by introducing a learned cloud mask and an appropriate evaluation scheme. Qualitative and quantitative experiments demonstrate superior performance of our approach over a wide variety of baseline methods, including leading approaches to satellite imagery forecasting. Additionally, we show how our modeled vegetation dynamics can be leveraged in a downstream task, inferring gross primary productivity for carbon monitoring. To the best of our knowledge, this work presents the first models for continental-scale vegetation modeling at fine resolution able to capture anomalies beyond the seasonal cycle, thereby paving the way for predictive assessments of vegetation status.

# Summary. An optional shortened abstract.
summary: ""

tags:
- Machine Learning for Earth Science
featured: false

links:
# - name: Custom Link
#   url: http://example.org
url_pdf: 'https://arxiv.org/pdf/2303.16198.pdf'
url_code: 'https://github.com/earthnet2021/earthnet-models-pytorch'
url_dataset: 'https://www.earthnet.tech/'
url_poster: ''
url_project: ''
url_slides: ''
url_source: ''
url_video: ''

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder. 
# image:
#   caption: ""
#   focal_point: ""
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
