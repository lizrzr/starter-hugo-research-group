---
title: 'Generative modeling in sinogram domain for sparse-view CT reconstruction'
authors:
  - Bing Guan
  - Cailian Yang
  - Liu Zhang
  - Shanzhou Niu
  - Minghui Zhang
  - Minghui Zhan
  - Yuhao Wang
  - Weiwen Wu
  - Qiegen Liu
author_notes:
  -
  - 
  -  
  -   
#  - 'Equal contribution'
date: '2023-8-28T00:00:00Z'
doi: '10.1109/TRPMS.2023.3309474'

# Schedule page publish date (NOT publication's date).
publishDate: '2023.8'

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ['2']

# Publication name and optional abbreviated publication name.
#publication: '*Journal of Source Themes, 1*(1)'
#publication_short: ''

abstract: The radiation dose in computed tomography (CT) examinations is harmful for patients but can be significantly reduced by intuitively decreasing the number of projection views. Reducing projection views usually leads to severe aliasing artifacts in reconstructed images. Previous deep learning (DL) techniques with sparse-view data require sparse-view/full-view CT image pairs to train the network with supervised manners. When the number of projection view changes, the DL network should be retrained with updated sparse-view/full-view CT image pairs. To relieve this limitation, we present a fully unsupervised score-based generative model in sinogram domain for sparse-view CT reconstruction. Specifically, we first train a score-based generative model on full-view sinogram data and use multichannel strategy to form high-dimensional tensor as the network input to capture their prior distribution. Then, at the inference stage, the stochastic differential equation (SDE) solver and data-consistency step were performed iteratively to achieve full-view projection. The filtered back projection (FBP) algorithm was used to achieve the final image reconstruction. Qualitative and quantitative studies were implemented to evaluate the presented method with several CT data. Experimental results demonstrated that our method achieved comparable or better performance than the supervised learning counterparts.

#tags:
#  - Source Themes
featured: false

# links:
# - name: ""
#   url: ""
#url_pdf: http://arxiv.org/pdf/1512.04133v1
url_code: ''
url_dataset: ''
url_poster: ''
url_project: ''
url_slides: ''
url_source: ''
url_video: ''

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder.
image:
  caption: 'Image credit: [**Unsplash**](https://unsplash.com/photos/jdD8gXaTZsc)'
  focal_point: ''
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
slides:
---
