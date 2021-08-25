---
# Documentation: https://sourcethemes.com/academic/docs/managing-content/

title: "Contrastive Language-Image Pre-training for the Italian Language"
authors: [Federico Bianchi, Giuseppe Attanasio, Raphael Pisoni, Silvia Terragni, Gabriele Sarti, Sri Lakshmi]
date: 2021-08-19T09:47:38+02:00
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: 2021-08-19T09:47:38+02:00

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["3"]

# Publication name and optional abbreviated publication name.
publication: "Arxiv Preprint"
publication_short: "Arxiv"

abstract: "CLIP (Contrastive Language-Image Pre-training) is a very recent multi-modal model that jointly learns representations of images and texts. The model is trained on a massive amount of English data and shows impressive performance on zero-shot classification tasks. Training the same model on a different language is not trivial, since data in other languages might be not enough and the model needs high-quality translations of the texts to guarantee a good performance. In this paper, we present the first CLIP model for the Italian Language (CLIP-Italian), trained on more than 1.4 million image-text pairs. Results show that CLIP-Italian outperforms the multilingual CLIP model on the tasks of image retrieval and zero-shot classification."

# Summary. An optional shortened abstract.
summary: "We present the first CLIP model for the Italian Language (CLIP-Italian), trained on more than 1.4 million image-text pairs."

tags: [Computer Vision, Natural Language Processing, Multimodality, Italian, HuggingFace, Deep Learning, Contrastive Learning, CLIP]
categories: [Multimodality]
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
  url: https://arxiv.org/abs/2108.08688v1
  icon_pack: fas
  icon: file-contract
- name: Model
  url: https://huggingface.co/clip-italian/clip-italian
  icon: codepen
  icon_pack: fab
- name: Code
  url: https://github.com/gsarti/cancer-detection
  icon_pack: fab
  icon: github
- name: Demo
  url: https://huggingface.co/spaces/clip-italian/clip-italian-demo
  icon_pack: fas
  icon: rocket

url_pdf: https://arxiv.org/pdf/2108.08688v1
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
projects: [clip-italian]

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
slides: ""
---