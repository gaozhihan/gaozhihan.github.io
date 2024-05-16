---
title: 'Fully Using Classifiers for Weakly Supervised Semantic Segmentation with Modified
  Cues'

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
- Ting Sun
- Lei Tai
- ZhihanGao
- Ming Liu
- Dit-Yan Yeung
# Author notes (optional)
author_notes:
  # - 'Equal contribution'
  # - 'Equal contribution'

date: '2019-04-03T00:00:00Z'
doi: ''

# Schedule page publish date (NOT publication's date).
publishDate: '2019-04-03T00:00:00Z'

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ["article"]

# Publication name and optional abbreviated publication name.
publication: 'arXiv preprint arXiv:1904.01749'
publication_short: arXiv 2019

abstract: This paper proposes a novel weakly-supervised semantic segmentation method using image-level label only. The class-specific activation maps from the well-trained classifiers are used as cues to train a segmentation network. The well-known defects of these cues are coarseness and incompleteness. We use super-pixel to refine them, and fuse the cues extracted from both a color image trained classifier and a gray image trained classifier to compensate for their incompleteness. The conditional random field is adapted to regulate the training process and to refine the outputs further. Besides initializing the segmentation network, the previously trained classifier is also used in the testing phase to suppress the non-existing classes. Experimental results on the PASCAL VOC 2012 dataset illustrate the effectiveness of our method.

# Summary. An optional shortened abstract.
# summary: 

tags: 
- Computer Vision

# Display this page in the Featured widget?
featured: false

# Custom links (uncomment lines below)
# links:
# - name: Custom Link
#   url: http://example.org

url_pdf: 'https://arxiv.org/pdf/1904.01749.pdf'
# url_code: ''
# url_dataset: ''
# url_poster: ''
# url_project: ''
# url_slides: ''
# url_source: ''
url_video: ''

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder.
image:
  caption: 'Training classifier and cue generation.'
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

