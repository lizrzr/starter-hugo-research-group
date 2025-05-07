---
title: 'Full image-index remainder based single low-dose DR/CT self-supervised denoising'
authors:
  - Yifei Long
  - Jiayi Pan
  - Yan Xi
  - Jianjia Zhang
  - Weiwen Wu
author_notes:
  -
  - 
  -  
  -   
  -  'communication' 
#  - 'Equal contribution'
date: '2023-10-01T00:00:00Z'
doi: '10.1109/TRPMS.2023.3309474'

# Schedule page publish date (NOT publication's date).
publishDate: '2023.10'

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ['1']

# Publication name and optional abbreviated publication name.
#publication: '*Journal of Source Themes, 1*(1)'
#publication_short: ''

abstract: Low-dose digital radiography (DR) and computed tomography (CT) play a crucial role in minimizing health risks during clinical examinations and diagnoses. However, reducing the radiation dose often leads to lower signal-to-noise ratio measurements, resulting in degraded image quality. Existing supervised and self-supervised reconstruction techniques have been developed with noisy and clean image pairs or noisy and noisy image pairs, implying they cannot be adapted to single DR and CT image denoising. In this study, we introduce the Full Image-Index Remainder (FIRE) method. Our method begins by dividing the entire high-dimensional image space into multiple low-dimensional sub-image spaces using a full image-index remainder technique. By leveraging the data redundancy present within these sub-image spaces, we identify similar groups of noisy sub-images for training a self-supervised denoising network. Additionally, we establish a sub-space sampling theory specifically designed for self-supervised denoising networks. Finally, we propose a novel regularization optimization function that effectively reduces the disparity between self-supervised and supervised denoising networks, thereby enhancing denoising training. Through comprehensive quantitative and qualitative experiments conducted on both clinical low-dose CT and DR datasets, we demonstrate the remarkable effectiveness and advantages of our FIRE method compared to other state-of-the-art approaches.

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
