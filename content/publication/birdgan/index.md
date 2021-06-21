---
title: "Learning 2D to 3D Lifting for Object Detection in 3D for Autonomous Vehicles"
authors:
- admin
- Gaurav Sharma
- Frederic Jurie
date: "2019-06-30T09:36:36+05:30"
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
publication_short: In *IROS 2021*

abstract: We address the problem of 3D object detection from 2D monocular images in autonomous driving scenarios. We propose to lift the 2D images to 3D representations using learned neural networks and leverage existing networks working directly on 3D data to perform 3D object detection and localization. We show that, with carefully designed training mechanism and automatically selected minimally noisy data, such a method is not only feasible, but gives higher results than many methods working on actual 3D inputs acquired from physical sensors. On the challenging KITTI benchmark, we show that our 2D to 3D lifted method outperforms many recent competitive 3D networks while significantly outperforming previous state-of-the-art for 3D detection from monocular images. We also show that a late fusion of the output of the network trained on generated 3D images, with that trained on real 3D images, improves performance. We find the results very interesting and argue that such a method could serve as a highly reliable backup in case of malfunction of expensive 3D sensors, if not potentially making them redundant, at least in the case of low human injury risk autonomous navigation scenarios like warehouse automation




# Summary. An optional shortened abstract.
summary:  IROS 2019

tags:
#- Source Themes
featured: true

links:
#- name: Custom Link
#  url: http://example.org
url_pdf: 'https://arxiv.org/pdf/1904.08494.pdf'
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