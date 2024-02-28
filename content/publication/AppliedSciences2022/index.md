---
title: "Hybrid Modeling of Deformable Linear Objects for Their Cooperative Transportation by Teams of Quadrotors"
authors:
 - admin
 - JM Lopez-Guede
 - G. Garate
 - M. Graña
date: "2022-04-07T00:00:00Z"
doi: "https://doi.org/10.3390/app12105253"

 # Schedule page publish date (NOT publication's date).
publishDate: ""

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["2"]

# Publication name and optional abbreviated publication name.
publication: "*Applied Sciences*, 12(10), 5253"
publication_short: "*Applied Sciences*, 12(10), 5253"

abstract: This paper deals with the control of a team of unmanned air vehicles (UAVs), specifically quadrotors, for which their mission is the transportation of a deformable linear object (DLO), i.e., a cable, hose or similar object in quasi-stationary state, while cruising towards destination. Such missions have strong industrial applications in the transportation of hoses or power cables to specific locations, such as the emergency power or water supply in hazard situations such as fires or earthquake damaged structures. This control must be robust to withstand strong and sudden wind disturbances and remain stable after aggressive maneuvers, i.e., sharp changes of direction or acceleration. To cope with these, we have previously developed the online adaptation of the proportional derivative (PD) controllers of the quadrotors thrusters, implemented by a fuzzy logic rule system that experienced adaptation by a stochastic gradient rule. However, sagging conditions appearing when the transporting drones are too close or too far away induce singularities in the DLO catenary models, breaking apart the control system. The paper’s main contribution is the formulation of the hybrid selective model of the DLO sections as either catenaries or parabolas, which allows us to overcome these sagging conditions. We provide the specific decision rule to shift between DLO models. Simulation results demonstrate the performance of the proposed approach under stringent conditions.

# Summary. An optional shortened abstract.
summary: The paper’s main contribution is the formulation of the hybrid selective model of the DLO sections as either catenaries or parabolas, which allows us to overcome these sagging conditions. We provide the specific decision rule to shift between DLO models. Simulation results demonstrate the performance of the proposed approach under stringent conditions.

tags:
- Quadrotors
- UAVs
- Control engineering
- Suspended loads
featured: false

links:
# - name: ""
#   url: ""
  - url_pdf: 'https://www.mdpi.com/2076-3417/12/10/5253'
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
  caption: 'Image credit: [**Applied Sciences**](https://www.mdpi.com/2076-3417/12/10/5253#)'
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
slides: example
---
