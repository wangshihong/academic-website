---
title: "Highway Icing Time Prediction with Deep Learning Approaches based on Data from Road Sensors"
authors:
- admin
- Tianle Wang
- Xuan Pei
- Hao Wang
- Qiang Zhu
- Tao Tang
- Taogang Hou
author_notes:
# - "Equal contribution"
date: "2023-06-12T00:00:00Z"
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: "2023-06-12T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["2"]

# Publication name and optional abbreviated publication name.
publication: In *Science China Technological Sciences*
# publication_short: "SCTS"

abstract: In harsh climates, highway icing poses a hazard to traffic safety and increases road maintenance costs. It is of great significance to predict when the highway icing may occur and take a preventive plan. However, there are few studies on highway icing time prediction due to the scarcity and complexity of data. In this study, variables of icing temperature, friction, ice percentage, road surface temperature, water film height, saline concentration, and road condition were collected by road sensors distributed on a highway in China. A large-scale time series highway surface information dataset called HighwayIce is formed. Furthermore, a deep learning approach called IceAlarm, composed of long short-term memory neural network (LSTM), multilayer perceptron (MLP), and residual connection, has been developed to predict when the highway will ice. The LSTM is used to process dynamic variables, the MLP is used to process static variables, and the fully-connected layers with residual connections are used to make a deep fusion. The experimental results show that the average mean absolute error before icing using the IceAlarm model is about 6 min and outperforms all baseline models. The HighwayIce dataset and IceAlarm model can help improve the prediction accuracy and efficiency of forecasting real-world road icing time, therefore reducing the impact of icy road conditions on traffic.

# Summary. An optional shortened abstract.
# summary: Lorem ipsum dolor sit amet, consectetur adipiscing elit. Duis posuere tellus ac convallis placerat. Proin tincidunt magna sed ex sollicitudin condimentum.

tags:
- Source Themes
featured: false

# links:
# - name: ""
#   url: ""
url_pdf: https://link.springer.com/article/10.1007/s11431-022-2230-8
- name: "Dataset"
# url_code: 'https://github.com/wowchemy/wowchemy-hugo-themes'
url_dataset: 'https://github.com/WangShihong'
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
