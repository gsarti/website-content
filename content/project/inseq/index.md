---
# Documentation: https://sourcethemes.com/academic/docs/managing-content/

title: "Inseq: An Interpretability Toolkit for Sequence Generation Models"
summary: "An open-source library to democratize access to model interpretability for sequence generation models"

authors: [Gabriele Sarti, Nils Feldhus, Oskar van der Waals, Ludwig Sickert]
tags: [Natural Language Processing, Interpretability, HuggingFace, Deep Learning]
categories: ["Interpretability"]

date: 2022-12-13

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
- name: Docs
  url: https://inseq.readthedocs.io/en/latest/
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

Inseq is a Pytorch-based hackable toolkit to democratize the study of interpretability for sequence generation models. Inseq supports a wide set of models from the 🤗 Transformers library and an ever-growing set of feature attribution methods, leveraging in part the widely-used Captum library. For a quick introduction to common use cases, see the [Getting started with Inseq](https://inseq.readthedocs.io/examples/quickstart.html) page.

Using Inseq, feature attribution maps that can be saved, reloaded, aggregated and visualized either as HTMLs (with Jupyter notebook support) or directly in the console using rich. Besides simple attribution, Inseq also supports features like step score extraction, attribution aggregation and attributed functions customization for more advanced use cases.
