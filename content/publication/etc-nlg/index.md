---
# Documentation: https://sourcethemes.com/academic/docs/managing-content/

title: "ETC-NLG: End-to-end Topic-Conditioned Natural Language Generation"
authors: [Ginevra Carbone, Gabriele Sarti]
date: 2020-12-01T09:47:38+02:00
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: 2020-08-26T09:47:38+02:00

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["2"]

# Publication name and optional abbreviated publication name.
publication: "Italian Journal of Computational Linguistics (IJCoL)"
publication_short: "IJCoL"

abstract: "Plug-and-play language models (PPLMs) enable topic-conditioned natural language generation by combining large pre-trained generators with attribute models to steer the predicted token distribution towards selected topics. Despite their efficiency, the large amounts of labeled texts required by PPLMs to effectively balance generation fluency and proper conditioning make them unsuitable to low-resource scenarios. We present ETC-NLG, an approach leveraging topic modeling annotations to produce End-to-end Topic-Conditioned Natural Language Generations over emergent topics in unlabeled document collections. We test our method’s effectiveness in a low-resource setting for Italian and perform a comparative evaluation of ETC-NLG for Italian and English using a parallel corpus. Finally, we propose an evaluation method to automatically estimate the conditioning effectiveness from generated utterances."

# Summary. An optional shortened abstract.
summary: "We present ETC-NLG, an approach leveraging topic modeling annotations to enable fully-unsupervised End-to-end Topic-Conditioned Natural Language Generation over emergent topics in unlabeled document collections."

tags: [Natural Language Processing, Deep Learning, Natural Language Generation, Topic Modeling, Transformers]
categories: []
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
  url: https://arxiv.org/abs/2008.10875
  icon_pack: fas
  icon: file-contract
- name: Journal
  url: https://journals.openedition.org/ijcol/728
  icon_pack: fas
  icon: file-contract

url_pdf: https://arxiv.org/pdf/2008.10875.pdf
url_code: https://github.com/gsarti/ETC-NLG
url_dataset:
url_poster:
url_project:
url_slides:
url_source:
url_video: https://vimeo.com/477513845

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