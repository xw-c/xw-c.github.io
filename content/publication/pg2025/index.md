---
title: "Fast Multi-Body Coupling for Underwater Interactions"
authors:
- Tianhong Gao
- admin
- Xingqiao Li 
- Wei Li
- Baoquan Chen
- Zherong Pan
- Kui Wu
- Mengyu Chu

date: "2025-10-18"
doi: "10.2312/pg.20251268"

# Schedule page publish date (NOT publication's date).
publishDate: "Oct. 2025"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["1"]

# Publication name and optional abbreviated publication name.
publication: In *Pacific Graphics 2025*
publication_short: In *PG 2025*

abstract: Simulating multi-rigid-body interactions in underwater environments is crucial for various downstream applications, such as robotic navigation, manipulation, and locomotion. However, existing approaches either rely on computationally expensive volumetric fluid-rigid simulations or focus solely on single-body dynamics. In this work, we introduce a fast framework for simulating multi-rigid-body coupling in underwater environments by extending the added mass paradigm to capture global interactions in incompressible, irrotational fluids. Our method solves a Boundary Integral Equation (BIE) for the potential flow field, from which we derive the governing equation of motion for multiple underwater rigid bodies using a variational principle. We evaluate our method across a range of underwater tasks, including object gripping and swimming. Compared to state-ofthe- art volumetric fluid solvers, our approach consistently reproduces similar behaviors while achieving up to 13× speedup. The example source code is available at https://github.com/guesss2022/fastMBCUI.

# Summary. An optional shortened abstract.
summary: Pacific Graphics 2025

links:
url_pdf: publications/pg2025underwaterbem.pdf
url_video: https://www.youtube.com/watch?v=REQUUZX_NrQ
url_code: https://github.com/guesss2022/fastMBCUI

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
