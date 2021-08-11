---
# Documentation: https://sourcethemes.com/academic/docs/managing-content/

title: "Contrastive Image-Text Pretraining for Italian"
summary: "The first CLIP model pretrained on the Italian language."

authors: [Federico Bianchi, Raphael Pisoni, Giuseppe Attanasio, Silvia Terragni, Dario Balestri, Gabriele Sarti, Sri Lakshmi]
tags: [Computer Vision, Natural Language Processing, Multimodality, Italian, HuggingFace, Deep Learning, Contrastive Learning, CLIP]
categories: ["Multimodality"]

date: 2021-07-23

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder. 
# Focal points: Smart, Center, TopLeft, Top, TopRight, Left, Right, BottomLeft, Bottom, BottomRight.
image:
  caption: ""
  focal_point: ""
  preview_only: false

# Custom links (optional).
#   Uncomment and edit lines below to show custom links.
links:
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

# Optional filename of your slides within your talk's folder or a URL.
url_slides:

url_code:
url_pdf: 
url_video:

# Markdown Slides (optional).
#   Associate this talk with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides = "example-slides"` references `content/slides/example-slides.md`.
#   Otherwise, set `slides = ""`.
slides: ""
---

CLIP is a multimodel model that can learn to represent images and text jointly in the same space. In this project, we aim to propose the first CLIP model trained on Italian data, that in this context can be considered a low resource language. Using a few techniques, we have been able to fine-tune a SOTA Italian CLIP model with only 1.4 million training samples.

For more information, refer to our [demo](https://huggingface.co/spaces/clip-italian/clip-italian-demo).
