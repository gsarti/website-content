---
# Documentation: https://sourcethemes.com/academic/docs/managing-content/

title: "Attributing Context Usage in Language Models"
summary: "An interpretability framework to detect and attribute context usage in language models' generations"

authors: [Gabriele Sarti, Jirui Qi, Grzegorz Chrupała, Malvina Nissim, Raquel Fernández, Arianna Bisazza]
tags: [Natural Language Processing, Interpretability, Deep Learning, Natural Language Generation]
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
- name: PECoRe Demo
  url: https://huggingface.co/spaces/gsarti/pecore
  icon_pack: fas
  icon: rocket
- name: MIRAGE Demo
  url: https://huggingface.co/spaces/gsarti/mirage
  icon_pack: fas
  icon: rocket
- name: PECoRe Repository
  url: https://github.com/gsarti/pecore
  icon_pack: fab
  icon: github
- name: MIRAGE Repository
  url: https://github.com/Betswish/MIRAGE
  icon_pack: fab
  icon: github
- name: Artifacts
  url: https://huggingface.co/collections/gsarti/pecore-iclr-2024-65edab42e28439e21b612c2e
  icon: codepen
  icon_pack: fab
- name: PECoRe Paper
  url: https://openreview.net/forum?id=XTHfNGI3zT
  icon_pack: fas
  icon: file-pdf
- name: MIRAGE Paper
  url: https://arxiv.org/abs/2406.13663
  icon_pack: fas
  icon: file-contract

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

PECoRe is a framework using the internal properties of generative language models to identify and attribute context usage in their generations. In particular, the framework is composed by two steps: Context-sensitive Token Identification (CTI), where generated tokens are classified as context-sensitive by contrastively comparing their probabilities with and without context, and Contextual Cues Imputation (CCI), where the dependence of token selected in the CTI step is highlighted by using contrastive attribution. The framework is integrated in the [Inseq interpretability library](https://github.com/inseq-team/inseq) and can be easily used thanks to the `inseq attribute-context` command. The framework is described in detail in the paper [Quantifying the Plausibility of Context Reliance in Neural Machine Translation](../publication/pecore), published at ICLR 2024, and its extension MIRAGE was created to support answer attribution in RAG applications [Model Internals-based Answer Attribution for Trustworthy Retrieval-Augmented Generation](../publication/mirage).