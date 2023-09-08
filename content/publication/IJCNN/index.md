---
title: "E-LMC: Extended Linear Model of Coregionalization for Spatial Field Prediction"
authors:
- admin
- Xueying Zhang
- Yichen Meng
- Wei W. Xing
author_notes:
# - "Equal contribution"
date: "2022-09-30T00:00:00Z"
doi: ""

# Schedule page publish date (NOT publication's date).
# publishDate: "2023-06-12T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["1"]

# Publication name and optional abbreviated publication name.
publication: In *2022 International Joint Conference on Neural Networks (IJCNN)*
# publication_short: In *SCTS*

abstract: Physical simulations based on partial differential equations typically generate spatial fields results, which are utilized to calculate specific properties of a system for engineering design and optimization. Due to the intensive computational burden of the simulations, a surrogate model mapping the low-dimensional inputs to the spatial fields are commonly built based on a relatively small dataset. To resolve the challenge of predicting the whole spatial field, the popular linear model of coregional-ization (LMC) can disentangle complicated correlations within the high-dimensional spatial field outputs and deliver accurate predictions. However, LMC fails if the spatial field cannot be well approximated by a linear combination of base functions with latent processes. In this paper, we present the Extended Linear Model of Coregionalization (E-LMC) by introducing an invertible neural network to linearize the highly complex and nonlinear spatial fields so that the LMC can easily generalize to nonlinear problems while preserving the traceability and scalability. Several real-world applications demonstrate that E-LMC can exploit spatial correlations effectively, showing a maximum improvement of about 40% over the original LMC and outperforming the other state-of-the-art spatial field models.

# Summary. An optional shortened abstract.
# summary: Lorem ipsum dolor sit amet, consectetur adipiscing elit. Duis posuere tellus ac convallis placerat. Proin tincidunt magna sed ex sollicitudin condimentum.

tags:
- Source Themes
featured: false

# links:
# - name: ""
#   url: ""
url_pdf: https://ieeexplore.ieee.org/abstract/document/9892976
url_code: 'https://github.com/WangShihong'
url_dataset: 'https://github.com/WangShihong'
url_poster: 'https://github.com/WangShihong'
# url_project: ''
# url_slides: ''
# url_source: ''
# url_video: ''

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder. 
# image:
#   caption: 'Image credit: [**Unsplash**](https://unsplash.com/photos/jdD8gXaTZsc)'
#   focal_point: ""
#   preview_only: false

# Associated Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `internal-project` references `content/project/internal-project/index.md`.
#   Otherwise, set `projects: []`.
# projects: []

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
