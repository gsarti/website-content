---
# Documentation: https://sourcethemes.com/academic/docs/managing-content/

title: "DivEMT: Neural Machine Translation Post-Editing Effort Across Typologically Diverse Languages"
authors: [Gabriele Sarti, Arianna Bisazza, Ana Guerberof Arenas, Antonio Toral]
date: 2022-05-24T01:00:00+02:00
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: 2022-05-24T01:00:00+02:00

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["1"]

# Publication name and optional abbreviated publication name.
publication: "In Proceedings of the 2022 Conference on Empirical Methods in Natural Language Processing"
publication_short: "EMNLP 2022"

abstract: "We introduce DivEMT, the first publicly available post-editing study of Neural Machine Translation (NMT) over a typologically diverse set of target languages. Using a strictly controlled setup, 18 professional translators were instructed to translate or post-edit the same set of English documents into Arabic, Dutch, Italian, Turkish, Ukrainian, and Vietnamese. During the process, their edits, keystrokes, editing times and pauses were recorded, enabling an in-depth, cross-lingual evaluation of NMT quality and post-editing effectiveness. Using this new dataset, we assess the impact of two state-of-the-art NMT systems, Google Translate and the multilingual mBART-50 model, on translation productivity. We find that post-editing is consistently faster than translation from scratch. However, the magnitude of productivity gains varies widely across systems and languages, highlighting major disparities in post-editing effectiveness for languages at different degrees of typological relatedness to English, even when controlling for system architecture and training data size. We publicly release the complete dataset including all collected behavioral data, to foster new research on the translation capabilities of NMT systems for typologically diverse languages."

# Summary. An optional shortened abstract.
summary: "We introduce DivEMT, the first publicly available post-editing study of Neural Machine Translation over a typologically diverse set of target languages."

tags: [Natural Language Processing, Post-editing, Machine Translation, Multilingual, Dataset, Behavioral Data]
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
  url: https://arxiv.org/abs/2205.12215
  icon_pack: fas
  icon: file-contract
- name: Dataset
  url: https://huggingface.co/datasets/GroNLP/divemt
  icon: codepen
  icon_pack: fab
- name: Code
  url: https://github.com/gsarti/divemt
  icon_pack: fab
  icon: github
- name: Demo
  url: https://huggingface.co/spaces/GroNLP/divemt_explorer
  icon_pack: fas
  icon: rocket

url_pdf: https://arxiv.org/pdf/2205.12215.pdf
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