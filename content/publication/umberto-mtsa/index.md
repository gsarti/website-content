---
# Documentation: https://sourcethemes.com/academic/docs/managing-content/

title: "UmBERTo-MTSA@ AcCompl-It: Improving Complexity and Acceptability Prediction with Multi-task Learning on Self-Supervised Annotations"
authors: [Gabriele Sarti]
date: 2020-12-19T09:47:38+02:00
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: 2020-12-19T09:47:38+02:00

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["1"]

# Publication name and optional abbreviated publication name.
publication: "In Proceedings of the Seventh Evaluation Campaign of Natural Language Processing and Speech Tools for Italian. Final Workshop (EVALITA 2020)"
publication_short: "In EVALITA 2020"

abstract: "This work describes a self-supervised data augmentation approach used to improve learning models' performances when only a moderate amount of labeled data is available. Multiple copies of the original model are initially trained on the downstream task. Their predictions are then used to annotate a large set of unlabeled examples. Finally, multi-task training is performed on the parallel annotations of the resulting training set, and final scores are obtained by averaging annotator-specific head predictions. Neural language models are fine-tuned using this procedure in the context of the AcCompl-it shared task at EVALITA 2020, obtaining considerable improvements in prediction quality."

# Summary. An optional shortened abstract.
summary: "This work describes a self-supervised data augmentation approach used to improve learning models' performances when only a moderate amount of labeled data is available."

tags: [Natural Language Processing, Deep Learning, Multi-task Learning, Transformers, Neural Language Models, Self-training]
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
  url: https://arxiv.org/abs/2011.05197
  icon_pack: fas
  icon: file-contract

url_pdf: http://ceur-ws.org/Vol-2765/paper92.pdf
url_code: https://github.com/gsarti/interpreting-complexity
url_dataset:
url_poster:
url_project:
url_slides:
url_source:
url_video: https://vimeo.com/487817662

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