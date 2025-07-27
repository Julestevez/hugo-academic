---
title: "Reinforcement Learning Based Trajectory Planning for Multi-UAV Load Transportation"
authors:
 - admin
 - JM Lopez-Guede
 - J. del Valle-Echavarri
 - M. Graña
date: "2024-10-09"
doi: "https://doi.org/10.1109/ACCESS.2024.3470509"

 # Schedule page publish date (NOT publication's date).
publishDate: ""

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["2"]

# Publication name and optional abbreviated publication name.
publication: "*IEEE Access*, 12, 144009"
publication_short: "*IEEE Access*, 12, 144009"

abstract: This study introduces a novel trajectory planning approach for the transportation of cable-suspended loads employing three quadrotors, relying on a reinforcement learning (RL) algorithm. The primary objective of this path planning method is to transport the cargo smoothly while avoiding its swing. Within this proposed solution, the value function of the RL is estimated through a feature vector and a parameter vector tailored to the specific problem. The parameter vector undergoes iterative updates via a batch method, subsequently guiding the generation of the desired trajectory through a greedy strategy. Ultimately, this desired trajectory is communicated to the quadrotor controller to ensure precise trajectory tracking. Simulation outcomes demonstrate the capability of the trained parameters to effectively fit the value function.

# Summary. An optional shortened abstract.
summary: This study introduces a novel trajectory planning approach for the transportation of cable-suspended loads employing three quadrotors, relying on a reinforcement learning (RL) algorithm. The primary objective of this path planning method is to transport the cargo smoothly while avoiding its swing.

tags:
- Quadrotors
- Reinforcement learning
- UAVs
- Control engineering
- Suspended-loads
- Artificial intelligence
featured: true

links:
# - name: ""
#   url: ""
  - url_pdf: 'https://ieeexplore.ieee.org/abstract/document/10699338'
# url_code: 'https://github.com/wowchemy/wowchemy-hugo-themes'
# url_dataset: ''
# url_poster: ''
# url_project: ''
# url_slides: ''
# url_source: ''
# url_video: ''

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder. 
image:
  caption: 'Image credit:[**IEEE**](https://ieeexplore.ieee.org/abstract/document/10699338)'
  focal_point: ""
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
# slides: example
---

