---
# Documentation: https://sourcethemes.com/academic/docs/managing-content/

title: "IT5: Text-to-text Pretraining for Italian Language Understanding and Generation"
authors: [Gabriele Sarti, Malvina Nissim]
date: 2024-05-20T01:00:00+02:00
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: 2024-05-20T01:00:00+02:00

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["1"]

# Publication name and optional abbreviated publication name.
publication: "Proceedings of the 2024 Joint International Conference on Computational Linguistics, Language Resources and Evaluation (LREC-COLING 2024)"
publication_short: "LREC-COLING 2024"

abstract: "We introduce IT5, the first family of encoder-decoder transformer models pretrained specifically on Italian. We document and perform a thorough cleaning procedure for a large Italian corpus and use it to pretrain four IT5 model sizes. We then introduce the ItaGen benchmark, which includes a broad range of natural language understanding and generation tasks for Italian, and use it to evaluate the performance of IT5 models and multilingual baselines. We find monolingual IT5 models to provide the best scale-to-performance ratio across tested models, consistently outperforming their multilingual counterparts and setting a new state-of-the-art for Italian language generation."

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
  url: https://huggingface.co/collections/gsarti/it5-lrec-coling-2024-6600468041d8fee2c42021c8
  icon: codepen
  icon_pack: fab
- name: Demo
  url: https://huggingface.co/spaces/gsarti/it5-demo
  icon_pack: fas
  icon: rocket

url_pdf: https://arxiv.org/pdf/2203.03759.pdf
url_code: https://github.com/gsarti/it5
url_dataset: https://huggingface.co/datasets/gsarti/clean_mc4_it
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