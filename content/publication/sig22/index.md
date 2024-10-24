---
title: "Simulation and Optimization of Magnetoelastic Thin Shells"
authors:
- admin
- Xingyu Ni
- Bo Zhu
- Bin Wang
- Baoquan Chen
date: "2022-07-09"
doi: "10.1145/3528223.3530142"

# Schedule page publish date (NOT publication's date).
publishDate: "Dec. 2022"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["2"]

# Publication name and optional abbreviated publication name.
publication: In *ACM Transactions on Graphics (Proceedings of SIGGRAPH 2022)*
publication_short: In *ACM TOG*

abstract: Magnetoelastic thin shells exhibit great potential in realizing versatile functionalities through a broad range of combination of material stiffness, remnant magnetization intensity, and external magnetic stimuli. In this paper, we propose a novel computational method for forward simulation and inverse design of magnetoelastic thin shells. Our system consists of two key components of forward simulation and backward optimization. On the simulation side, we have developed a new continuum mechanics model based on the Kirchhoff–Love thin-shell model to characterize the behaviors of a megnetolelastic thin shell under external magnetic stimuli. Based on this model, we proposed an implicit numerical simulator facilitated by the magnetic energy Hessian to treat the elastic and magnetic stresses within a unified framework, which is versatile to incorporation with other thin shell models. On the optimization side, we have devised a new differentiable simulation framework equipped with an efficient adjoint formula to accommodate various PDE-constraint, inverse design problems of magnetoelastic thin-shell structures, in both static and dynamic settings. It also encompasses applications of magnetoelastic soft robots, functional Origami, artworks, and meta-material designs. We demonstrate the efficacy of our framework by designing and simulating a broad array of magnetoelastic thin-shell objects that manifest complicated interactions between magnetic fields, materials, and control policies.

# Summary. An optional shortened abstract.
summary: ACM Transactions on Graphics (Proceedings of SIGGRAPH 2022)

links:
- name: Bilibili
  url: https://www.bilibili.com/video/BV17Y411T7xP
- name: Youtube
  url: https://youtu.be/TeHcg75m9Vw
- name: low-res PDF
  url: publications/sig24MagThinShells.pdf
url_pdf: publications/sig24MagThinShells.pdf
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
