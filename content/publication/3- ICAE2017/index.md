---
title: "Online fuzzy modulated adaptive PD control for cooperative aerial transportation of deformable linear objects"
authors:
 - admin
 - M. Graña
 - JM Lopez-Guede
date: "2017-04-07T00:00:00Z"
doi: "https://doi.org/10.3233/ICA-160530"

 # Schedule page publish date (NOT publication's date).
publishDate: ""

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["2"]

# Publication name and optional abbreviated publication name.
publication: ""
publication_short: "*Integrated Computer-Aided Engineering*, 24(1), 41-55"

abstract: The aim of this work is to design robust control algorithms of aerial robots, i.e. quadrotors, for team transportation of a deformable linear object (DLO). The DLO-robot attachment makes the whole system physically coupled by an elastic element, which introduces strong non-linearities in the system dynamics. Sections in quasi-stationary state of the DLO hanging freely from two extreme points can be modeled by catenary curves, so we are able to build a detailed and accurate simulation of the system as the workbench for the evaluation of alternative quadrotor control approaches. DLO transportation is an instance of a follow the leader team strategy, in which the local quadrotor control must cope with the dynamic perturbations due to the DLO linking the quadrotors. The quadrotor team control has two phases, one achieving a spatial configuration with equal energy consumption, the other is to manage the horizontal motion which is the transportation process per se. In this paper we deal with the second control problem, assuming the first solved. We use proportional derivative (PD) controllers for both quadrotor attitude and trajectory control. Offline PD parameter setting carried by metaheuristic optimization can not cope with the perturbations induced by the DLO and environmental conditions, i.e. wind shear. Therefore we propose an adaptive controller for the quadrotors carrying out the DLO transportation task which uses fuzzy modeling of the error in order to modulate the activation of the PD parameters adaptation rules, which are error gradient descent rules. Computational experiments on our system simulation workbench show that our adaptive approach scales well when increasing the number of quadrotors, providing smooth follow-the-leader team strategy navigation behaviors even under strong wind perturbation conditions. We compare our approach with other state-of-the-art online and offline approaches.

# Summary. An optional shortened abstract.
summary: Lorem ipsum dolor sit amet, consectetur adipiscing elit. Duis posuere tellus ac convallis placerat. Proin tincidunt magna sed ex sollicitudin condimentum.

tags:
- Quadrotors
featured: false

links:
# - name: ""
#   url: ""
  - url_pdf: 'https://content.iospress.com/articles/integrated-computer-aided-engineering/ica530'
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
  caption: 'Image credit: [**Unsplash**](https://unsplash.com/photos/jdD8gXaTZsc)'
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



{{% callout note %}}
Click the *Cite* button above to demo the feature to enable visitors to import publication metadata into their reference management software.
{{% /callout %}}

{{% callout note %}}
Create your slides in Markdown - click the *Slides* button to check out the example.
{{% /callout %}}

Supplementary notes can be added here, including [code, math, and images](https://wowchemy.com/docs/writing-markdown-latex/).
