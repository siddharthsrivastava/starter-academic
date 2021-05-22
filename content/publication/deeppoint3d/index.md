---
title: "Deeppoint3d: Learning discriminative local descriptors using deep metric learning on 3d point clouds"
authors:
- admin
- Brejesh Lall
date: "2019-010-25T09:36:36+05:30"
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: "2020-03-25T09:36:36+05:30"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["2"]

# Publication name and optional abbreviated publication name.
publication: In *Elsevier Pattern Recognition Letters*
publication_short: In *PRL 2019*

abstract: Learning local descriptors is an important problem in computer vision. While there are many techniques for learning local patch descriptors for 2D images, recently efforts have been made for learning local descriptors for 3D points. The recent progress towards solving this problem in 3D leverages the strong feature representation capability of image based convolutional neural networks by utilizing RGB-D or multi-view representations. However, in this paper, we propose to learn 3D local descriptors by directly processing unstructured 3D point clouds without needing any intermediate representation. The method constitutes a deep network for learning permutation invariant representation of 3D points. To learn the local descriptors, we use a multi-margin contrastive loss which discriminates between similar and dissimilar points on a surface while also leveraging the extent of dissimilarity among the negative samples at the time of training. With comprehensive evaluation against strong baselines, we show that the proposed method outperforms state-of-the-art methods for matching points in 3D point clouds. Further, we demonstrate the effectiveness of the proposed method on various applications achieving state-of-the-art results.


# Summary. An optional shortened abstract.
summary:  PRL 2019

tags:
#- Source Themes
featured: true

links:
#- name: Custom Link
url: 
url_pdf: 'https://arxiv.org/pdf/1904.00817.pdf'
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
  caption: ''
  focal_point: ""
  preview_only: false

# Associated Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `internal-project` references `content/project/internal-project/index.md`.
#   Otherwise, set `projects: []`.
projects: []
#- internal-project

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
#slides: example
---