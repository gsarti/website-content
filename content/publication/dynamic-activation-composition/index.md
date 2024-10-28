---
# Documentation: https://sourcethemes.com/academic/docs/managing-content/

title: "Multi-property Steering of Large Language Models with Dynamic Activation Composition"
authors: [Daniel Scalena, Gabriele Sarti, Malvina Nissim]
date: 2024-06-26T00:00:00+02:00
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: 2024-06-26T00:00:00+02:00

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["1"]

# Publication name and optional abbreviated publication name.
publication: "Seventh BlackboxNLP Workshop on Analyzing and Interpreting Neural Networks for NLP"
publication_short: "BlackboxNLP 2024"

abstract: "Activation steering methods were shown to be effective in conditioning language model generation by additively intervening over models' intermediate representations. However, the evaluation of these techniques has so far been limited to single conditioning properties and synthetic settings. In this work, we conduct a comprehensive evaluation of various activation steering strategies, highlighting the property-dependent nature of optimal parameters to ensure a robust effect throughout generation. To address this issue, we propose Dynamic Activation Composition, an information-theoretic approach to modulate the steering intensity of one or more properties throughout generation. Our experiments on multi-property steering show that our method successfully maintains high conditioning while minimizing the impact of conditioning on generation fluency."

# Summary. An optional shortened abstract.
summary: "We propose Dynamic Activation Composition, an adaptive approach for multi-property activation steering of LLMs"

tags: [Natural Language Processing, Deep Learning, Interpretability, Style Transfer, Multilingual, Prompting, Large Language Models]
categories: [Natural Language Processing]
featured: true

# Custom links (optional).
#   Uncomment and edit lines below to show custom links.
# links:
# - name: Follow
#   url: https://twitter.com
#   icon_pack: fab
#   icon: twitter
links:
- name: ArXiv
  url: https://arxiv.org/abs/2406.17563
  icon_pack: fas
  icon: file-contract
- name: Repository
  url: https://github.com/DanielSc4/Dynamic-Activation-Composition
  icon_pack: fab
  icon: github

url_pdf: https://arxiv.org/pdf/2406.17563.pdf
url_code:
url_dataset:
url_poster:
url_project:
url_slides:
url_source:
url_video:

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder. 
# Focal points: Smart, Center, TopLeft, Top, TopRight, Left, Right, BottomLeft, Bottom, BottomRight.
image:
  caption: ""
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
slides: ""
---