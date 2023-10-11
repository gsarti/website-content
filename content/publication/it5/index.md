---
# Documentation: https://sourcethemes.com/academic/docs/managing-content/

title: "IT5: Large-scale Text-to-text Pretraining for Italian Language Understanding and Generation"
authors: [Gabriele Sarti, Malvina Nissim]
date: 2022-03-09T01:00:00+02:00
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: 2022-03-08T01:00:00+02:00

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["3"]

# Publication name and optional abbreviated publication name.
publication: "Arxiv Preprint"
publication_short: "Arxiv"

abstract: "The T5 model and its unified text-to-text paradigm contributed in advancing the state-of-the-art for many natural language processing tasks. While some multilingual variants of the T5 model have recently been introduced, their performances were found to provide suboptimal performances for languages other than English if compared to monolingual variants. We are motivated by these findings to introduce IT5, the first family of encoder-decoder transformer models pretrained specifically on Italian. We perform a thorough cleaning of a web-crawled Italian corpus including more than 40 billion words and use it to pretrain three IT5 models of different sizes. The performance of IT5 models and their multilingual counterparts is then evaluated on a broad range of natural language understanding and generation benchmarks for Italian. We find the monolingual IT5 models to provide the best scale-to-performance ratio across tested models, consistently outperforming their multilingual counterparts and setting a new state-of-the-art for most Italian conditional language generation tasks."

# Summary. An optional shortened abstract.
summary: "IT5s are the first encoder-decoder transformers pretrained on more than 40 billion Italian words."

tags: [Natural Language Processing, Pre-training, Italian, HuggingFace, Deep Learning, T5, Conditional Language Generation, Multilingual]
categories: [Natural Language Processing]
featured: false

# Custom links (optional).
#   Uncomment and edit lines below to show custom links.
# links:
# - name: Follow
#   url: https://twitter.com
#   icon_pack: fab
#   icon: twitter
links:
- name: ArXiv
  url: https://arxiv.org/abs/2203.03759
  icon_pack: fas
  icon: file-contract
- name: Models
  url: https://huggingface.co/it5
  icon: codepen
  icon_pack: fab
- name: Code
  url: https://github.com/gsarti/it5
  icon_pack: fab
  icon: github
- name: Demo
  url: https://huggingface.co/spaces/it5/it5-demo
  icon_pack: fas
  icon: rocket

url_pdf: https://arxiv.org/pdf/2203.03759.pdf
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
projects: [it5]

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
slides: ""
---