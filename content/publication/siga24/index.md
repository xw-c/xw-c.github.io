---
title: "A Time-Dependent Inclusion-Based Method for Continuous Collision
 Detection between Parametric Surfaces"
authors:
- admin
- Cheng Yu
- Xingyu Ni
- Mengyu Chu
- Bin Wang
- Baoquan Chen
date: "2024-11-01"
doi: "10.1145/3687960"

# Schedule page publish date (NOT publication's date).
publishDate: "Nov. 2024"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["2"]

# Publication name and optional abbreviated publication name.
publication: In *ACM Transactions on Graphics (SIGGRAPH Asia 2024 Journal Papers)*
publication_short: In *ACM TOG*

abstract:  Continuous collision detection (CCD) between parametric surfaces is typically formulated as a five-dimensional constrained optimization problem. In the field of CAD and computer graphics, common approaches to solving this problem rely on linearization or sampling strategies. Alternatively, inclusion-based techniques detect collisions by employing 5D inclusion functions, which are typically designed to represent the swept volumes of parametric surfaces over a given time span, and narrowing down the earliest collision moment through subdivision in both spatial and temporal dimensions. However, when high detection accuracy is required, all these approaches significantly increases computational consumption due to the  high-dimensional searching space. In this work, we develop a new time-dependent inclusion-based CCD framework that eliminates the need for temporal subdivision and can speedup conventional methods by a factor ranging from 36 to 138. To achieve this, we propose a novel time-dependent inclusion function that provides a continuous representation of a moving surface, along with a corresponding intersection detection algorithm that quickly identifies the time intervals when collisions are likely to occur. We validate our method across various primitive types, demonstrate its efficacy within the simulation pipeline and show that it significantly improves CCD efficiency while maintaining accuracy.

# Summary. An optional shortened abstract.
summary: ACM Transactions on Graphics (SIGGRAPH Asia 2024 Journal Papers)
# tags:
# - Source Themes
# featured: false

# links:
# - name: ""
#   url: ""
url_pdf: publications/siga24TDIF.pdf
# url_pdf: http://arxiv.org/pdf/1512.04133v1
url_code: 'https://github.com/xw-c/TDIB-CCD'
# url_dataset: ''
# url_poster: ''
# url_project: ''
# url_slides: ''
# url_source: ''
# url_video: ''

# Associated Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `internal-project` references `content/project/internal-project/index.md`.
#   Otherwise, set `projects: []`.
projects: []

---
