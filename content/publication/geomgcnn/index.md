---
title: "Exploiting Local Geometry for Feature and Graph Construction 
for Better 3D Point Cloud Processing with Graph Neural Networks"
authors:
- admin
- Gaurav Sharma
date: "2021-03-25T09:36:36+05:30"
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: "2021-03-25T09:36:36+05:30"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["1"]

# Publication name and optional abbreviated publication name.
publication: In *International Conference on Robotics and Automation 2021*
publication_short: In *ICRA 2021*

abstract: We propose simple yet effective improvements in point representations and local neighborhood graph construction within the general framework of graph neural networks (GNNs) for 3D point cloud processing. As a first contribution, we propose to augment the vertex representations with important local geometric information of the points, followed by nonlinear projection using a MLP. As a second contribution, we propose to improve the graph construction for GNNs for 3D point clouds. The existing methods work with a knn based approach for constructing the local neighborhood graph. We argue that it might lead to reduction in coverage in case of dense sampling by sensors in some regions of the scene. The proposed methods aims to counter such problems and improve coverage in such cases. As the traditional GNNs were designed to work with general graphs, where vertices may have no geometric interpretations, we see both our proposals as augmenting the general graphs to incorporate the geometric nature of 3D point clouds. While being simple, we demonstrate with multiple challenging benchmarks, with relatively clean CAD models based, as well as with real world noisy scans, that the proposed method achieves state of the art results on benchmarks for 3D classification (ModelNet40) , part segmentation (ShapeNet) and semantic segmentation (Stanford 3D Indoor Scenes Dataset). We also show that the proposed network achieves faster training convergence, e.g. ~40% less epochs for classification.

# Summary. An optional shortened abstract.
summary:  ICRA 2021

tags:
#- Source Themes
featured: true

links:
#- name: Custom Link
#  url: http://example.org
url_pdf: '#'
url_code: '#'
url_dataset: ''
url_poster: ''
url_project: ''
url_slides: ''
url_source: ''
url_video: '#'

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
projects:
- internal-project

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
#slides: example
---