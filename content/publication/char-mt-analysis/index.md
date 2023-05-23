---
# Documentation: https://sourcethemes.com/academic/docs/managing-content/

title: "Are Character-level Translations Worth the Wait? Comparing Character- and Subword-level Models for Machine Translation"
authors: [Lukas Edman, Gabriele Sarti, Antonio Toral, Gertjan van Noord, Arianna Bisazza]
date: 2023-02-28T09:47:38+02:00
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: 2023-02-28T09:47:38+02:00

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["3"]

# Publication name and optional abbreviated publication name.
publication: "Arxiv Preprint"
publication_short: "Arxiv"

abstract: "Pretrained character-level language models were recently shown to be competitive with popular subword models across a range of NLP tasks. However, there has been little research on their effectiveness for neural machine translation (NMT). This work performs an extensive comparison across multiple languages and experimental conditions of state-of-the-art character- and subword-level pre-trained models (ByT5 and mT5, respectively) on NMT, showing the effectiveness of character-level modeling in translation, particularly in cases where training data is limited. In our analysis, we show how character models' performance gains are reflected in better translations of orthographically similar words and rare words. While evaluating the importance of source texts in driving model predictions, we highlight ByT5 word-level patterns suggesting an ability to modulate word and character-level information during the translation, providing insights into a potential weakness of character-level modeling. We conclude by assessing the efficiency tradeoff of character models, suggesting their usage in non-time-critical scenarios to boost translation quality."

# Summary. An optional shortened abstract.
summary: "We compare subword and character-level MT models, showing the effectiveness of the latters in low-resource settings. We adopt feature attribution to discover that character model implicitly learn to modulate word and character-level information during the translation."

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