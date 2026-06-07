---
title: "Floating-Point Robustness in Parametric Surface Continuous Collision Detection: From Algorithm to Benchmarking"
authors:
- admin
- Junyu Wang
- Cheng Yu
- Xingyu Ni
- Meng Zhang
- Bin Wang
- Mengyu Chu
- Baoquan Chen
author_notes:
- "Equal contribution"
- "Equal contribution"
date: "2026-06-06"
doi: "10.1145/3811310"
# Schedule page publish date (NOT publication's date).
publishDate: "July. 2026"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["2"]

# Publication name and optional abbreviated publication name.
publication: In *ACM Transactions on Graphics (SIGGRAPH 2026 Journal Papers)*
publication_short: In *ACM TOG*

abstract: Continuous Collision Detection is essential in simulation and modeling for accurately identifying object collisions. While robust CCD techniques have matured for triangle meshes, ensuring floating-point robustness for parametric surfaces remains an open challenge due to their representational complexity and heightened algorithmic sensitivity. In this paper, we present the first floating-point-robust CCD framework for parametric surfaces. Built on the Time-Dependent Inclusion-Based Method (TDIBM), our approach introduces a novel error decomposition strategy that separates coefficient and arithmetic errors, enabling structured analysis and safety guarantees. To rigorously benchmark robustness, we develop a rational arithmetic-based dataset by inverting the CCD process --- we generate exact ground-truth datasets from prescribed collision outcomes. Our construction captures both typical scenarios and near-degenerate cases. We evaluate several CCD algorithms using this benchmark to provide an in-depth analysis. Together, our method and dataset establish a comprehensive foundation for analyzing, benchmarking, and improving floating-point robustness in parametric surface CCD. Code and dataset will be published upon acceptance.

# Summary. An optional shortened abstract.
summary: ACM Transactions on Graphics (SIGGRAPH 2026 Journal Papers)

# links:
# - name: Bilibili
#   url: https://www.bilibili.com/video/BV17Y411T7xP
# - name: Youtube
#   url: https://youtu.be/TeHcg75m9Vw
# - name: low-res PDF
#   url: publications/sig22MagThinShells-lowres.pdf
url_pdf: publications/sig26CCDdataset.pdf
# url_video: '#'

# # Featured image
# # To use, add an image named `featured.jpg/png` to your page's folder. 
# image:
#   caption: 'Image credit: [**Unsplash**](https://unsplash.com/photos/pLCdAaMFLTE)'
#   focal_point: ""
#   preview_only: false

# # Associated Projects (optional).
# #   Associate this publication with one or more of your projects.
# #   Simply enter your project's folder or file name without extension.
# #   E.g. `internal-project` references `content/project/internal-project/index.md`.
# #   Otherwise, set `projects: []`.
projects: []
# - internal-project

# # Slides (optional).
# #   Associate this publication with Markdown slides.
# #   Simply enter your slide deck's filename without extension.
# #   E.g. `slides: "example"` references `content/slides/example/index.md`.
# #   Otherwise, set `slides: ""`.
# slides: example
---
