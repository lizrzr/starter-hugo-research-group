---
title: 'Deep Learning based spectral CT Imaging'
authors:
  - Weiwen Wu
  - Lieza Vanden Broeke
  - Fenglin Liu
  - Varut Vardhanabhuti
  - Ge Wang
author_notes:
  - 
  - 
  - 
  - 'communication'
#  - 'Equal contribution'
date: '2021-12-01T00:00:00Z'
doi: '10.1016/j.neunet.2021.08.026'

# Schedule page publish date (NOT publication's date).
publishDate: '2021.12'

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ['2']

# Publication name and optional abbreviated publication name.
#publication: '*Journal of Source Themes, 1*(1)'
#publication_short: ''

abstract: Spectral computed tomography (CT) has attracted much attention in radiation dose reduction, metal artifacts removal, tissue quantification and material discrimination. The x-ray energy spectrum is divided into several bins, each energy-bin-specific projection has a low signal-noise-ratio (SNR) than the current-integrating counterpart, which makes image reconstruction a unique challenge. Traditional wisdom is to use prior knowledge based iterative methods. However, this kind of methods demands a great computational cost. Inspired by deep learning, here we first develop a deep learning based reconstruction method; i.e., U-net with -norm, Total variation, Residual learning, and Anisotropic adaption (ULTRA). Specifically, we emphasize the various multi-scale feature fusion and multichannel filtering enhancement with a denser connection encoding architecture for residual learning and feature fusion. To address the image deblurring problem associated with the - loss, we propose a general -loss, . Furthermore, the images from different energy bins share similar structures of the same object, the regularization characterizing correlations of different energy bins is incorporated into the - loss function, which helps unify the deep learning based methods with traditional compressed sensing based methods. Finally, the anisotropically weighted total variation is employed to characterize the sparsity in the spatial–spectral domain to regularize the proposed network In particular, we validate our ULTRA networks on three large-scale spectral CT datasets, and obtain excellent results relative to the competing algorithms. In conclusion, our quantitative and qualitative results in numerical simulation and preclinical experiments demonstrate that our proposed approach is accurate, efficient and robust for high-quality spectral CT image reconstruction.

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
