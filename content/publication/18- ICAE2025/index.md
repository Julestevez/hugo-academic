---
title: "Enhanced Dynamic Obstacle Avoidance for Linked Multi-Agent Systems by an Extended Hybrid Reciprocal Velocity Obstacle Model"
authors:
 - admin
 - JM Lopez-Guede
 - J. del Valle-Echavarri
 - D. Caballero-Martin
 - M. Graña
date: "2025-07-05"
doi: "https://doi.org/10.1109/ACCESS.2024.3470509"

 # Schedule page publish date (NOT publication's date).
publishDate: ""

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["2"]

# Publication name and optional abbreviated publication name.
publication: "*Integrated Computer-Aided Engineering*, 12, 144009"
publication_short: "*ICAE*, 12, 144009"

abstract: Obstacle avoidance is a critical issue in autonomous agent spatial navigation, moreover in the case of team coordinated
navigation with moving obstacles. Algorithms for obstacle avoidance by unconstrained teams of agents, i.e. agents
that have no relative position restrictions, such as the Reciprocal Velocity Obstacle (RVO), and the Hybrid Reciprocal
Velocity Obstacle (HRVO) have been proposed in the literature. However, in some tasks the agents must comply with
relative spatial restrictions, i.e. agents must maintain specific distances between them within some tolerance thresholds.
These tasks include robotic team coordination, human-robot collaboration and autonomous vehicle platooning. This
paper presents a novel Extended Hybrid Reciprocal Velocity Obstacle (EHRVO) algorithm for multi-agent collision
avoidance that incorporates linked agent constraints. The proposed approach introduces proximity constraints between
paired agents while adapting the collision avoidance geometry to maintain these relationships. This research work
extends the HRVO framework to create a hierarchical set of constraints that prioritize maintenance of spatial consistent
agent pairs or triads while ensuring collision-free trajectories. Prior to actual physical implementation, the EHRVO
navigation algorithm is validated through exhaustive simulations involving multiple paired agents and triads navigating
in cluttered spaces with many moving obstacles, namely the agents in the other teams. Results demonstrate that this
novel approach successfully maintains the spatial relative positions of linked group agents while avoiding collisions
with other agents, showing significant improvements over traditional RVO and HRVO algorithms in scenarios requiring
coordinated movement.

# Summary. An optional shortened abstract.
summary: This paper presents a novel Extended Hybrid Reciprocal Velocity Obstacle (EHRVO) algorithm for multi-agent collision
avoidance that incorporates linked agent constraints. The proposed approach introduces proximity constraints between paired agents while adapting the collision avoidance geometry to maintain these relationships. This research work extends the HRVO framework to create a hierarchical set of constraints that prioritize maintenance of spatial consistent agent pairs or triads while ensuring collision-free trajectories. .

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

