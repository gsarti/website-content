---
# Documentation: https://sourcethemes.com/academic/docs/managing-content/

title: "Are Character-level Translations Worth the Wait? Comparing ByT5 and mT5 for Machine Translation"
authors: [Lukas Edman, Gabriele Sarti, Antonio Toral, Gertjan van Noord, Arianna Bisazza]
date: 2023-02-28T09:47:38+02:00
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: 2023-02-28T09:47:38+02:00

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["2"]

# Publication name and optional abbreviated publication name.
publication: "Transactions of the Association for Computational Linguistics (2024) 12: 392–410"
publication_short: "TACL"

abstract: "Pretrained character-level and byte-level language models have been shown to be competitive with popular subword models across a range of Natural Language Processing tasks. However, there has been little research on their effectiveness for neural machine translation (NMT), particularly within the popular pretrain-then-finetune paradigm. This work performs an extensive comparison across multiple languages and experimental conditions of character- and subword-level pretrained models (ByT5 and mT5, respectively) on NMT. We show the effectiveness of character-level modeling in translation, particularly in cases where fine-tuning data is limited. In our analysis, we show how character models’ gains in translation quality are reflected in better translations of orthographically similar words and rare words. While evaluating the importance of source texts in driving model predictions, we highlight word-level patterns within ByT5, suggesting an ability to modulate word-level and character-level information during generation. We conclude by assessing the efficiency tradeoff of byte models, suggesting their usage in non-time-critical scenarios to boost translation quality."

# Summary. An optional shortened abstract.
summary: "We analyze input contributions of char-level MT models and show how they modulate word and character-level information."

tags: [Natural Language Processing, Deep Learning, Interpretability, Machine Translation, Feature Attribution, Character-level]
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
- name: Journal
  url: https://direct.mit.edu/tacl/article/doi/10.1162/tacl_a_00651/120650/Are-Character-level-Translations-Worth-the-Wait
  icon_pack: fas
  icon: file-contract
- name: ArXiv
  url: https://arxiv.org/abs/2302.14220
  icon_pack: fas
  icon: file-contract
- name: Hugging Face
  url: https://huggingface.co/papers/2302.14220
  icon: codepen
  icon_pack: fab

url_pdf: https://arxiv.org/pdf/2302.14220.pdf
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