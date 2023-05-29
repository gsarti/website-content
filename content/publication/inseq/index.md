---
# Documentation: https://sourcethemes.com/academic/docs/managing-content/

title: "Inseq: An Interpretability Toolkit for Sequence Generation Models"
authors: [Gabriele Sarti, Nils Feldhus, Ludwig Sickert, Oskar van der Wal]
date: 2023-02-27T09:47:38+02:00
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: 2023-02-27T09:47:38+02:00

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["1"]

# Publication name and optional abbreviated publication name.
publication: "In Proceedings of the 61st Annual Meeting of the Association for Computational Linguistics: System Demonstrations Track"
publication_short: "ACL Demo 2023"

abstract: "Past work in natural language processing interpretability focused mainly on popular classification tasks while largely overlooking generation settings, partly due to a lack of dedicated tools. In this work, we introduce Inseq, a Python library to democratize access to interpretability analyses of sequence generation models. Inseq enables intuitive and optimized extraction of models' internal information and feature importance scores for popular decoder-only and encoder-decoder Transformers architectures. We showcase its potential by adopting it to highlight gender biases in machine translation models and locate factual knowledge inside GPT-2. Thanks to its extensible interface supporting cutting-edge techniques such as contrastive feature attribution, Inseq can drive future advances in explainable natural language generation, centralizing good practices and enabling fair and reproducible model evaluations."

# Summary. An optional shortened abstract.
summary: "We present Inseq, a Python library to democratize access to interpretability analyses of sequence generation models."

tags: [Natural Language Processing, HuggingFace, Deep Learning, Interpretability, Machine Translation, Transformers, Feature Attribution, Natural Language Generation, Library]
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
  url: https://arxiv.org/abs/2302.13942
  icon_pack: fas
  icon: file-contract
- name: Docs
  url: https://inseq.readthedocs.io
  icon_pack: fas
  icon: book
- name: Repository
  url: https://github.com/inseq-team/inseq
  icon_pack: fab
  icon: github
- name: PyPI
  url: https://pypi.org/project/inseq/
  icon_pack: fab
  icon: python
- name: Twitter
  icon: twitter
  icon_pack: fab
  url: https://twitter.com/InseqDev
- name: Mastodon
  icon: mastodon
  icon_pack: fab
  link: https://sigmoid.social/@inseq
- name: Hugging Face
  url: https://huggingface.co/inseq
  icon: codepen
  icon_pack: fab
- name: Demo
  url: https://huggingface.co/spaces/oskarvanderwal/MT-bias-demo
  icon_pack: fas
  icon: rocket

url_pdf: https://arxiv.org/pdf/2302.13942
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
projects: [inseq]

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
slides: ""
---