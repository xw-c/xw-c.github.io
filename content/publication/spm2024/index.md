---
title: "Simulating Thin Shells by Bicubic Hermite Elements"
authors:
- Xingyu Ni*
- Xuwen Chen*
- Cheng Yu
- Bin Wang
- Baoquan Chen
date: "2024-10-24"
doi: "10.1016/j.cad.2024.103734"

# Schedule page publish date (NOT publication's date).
publishDate: "Sept. 2024"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["2"]

# Publication name and optional abbreviated publication name.
publication: In *Computer-Aided Design (Proceedings of SPM 2024)*
publication_short: In *ACM TOG*

abstract: In this study, we present the bicubic Hermite element method (BHEM), a new computational framework devised for the elastodynamic simulation of thin-shell structures. The BHEM is constructed based on quadrilateral Hermite patches, which serve as a unified representation for shell geometry, simulation, collision avoidance, as well as rendering. Compared with the commonly utilized linear FEM, the BHEM offers higher-order solution spaces, enabling the capture of more intricate and smoother geometries while employing significantly fewer finite elements. In comparison to other high-order methods, the BHEM achieves conforming $C^1$ continuity for Kirchhoff–Love (KL) shells with minimal complexity. Furthermore, by leveraging the subdivision and convex hull properties of Hermite patches, we develop an efficient algorithm for ray-patch intersections, facilitating collision handling in simulations and ray tracing in rendering. This eliminates the need for laborious remodeling of the pre-existing surface as the conventional approaches do. We substantiate our claims with comprehensive experiments, which demonstrate the high accuracy and versatility of the proposed method.

# Summary. An optional shortened abstract.
summary: Computer-Aided Design (Proceedings of SPM 2024)

links:
url_pdf: publications/spm24BHEM.pdf
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
