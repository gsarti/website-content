---
# Documentation: https://sourcethemes.com/academic/docs/managing-content/

title: "ETC-NLG: End-to-end Topic-Conditioned Natural Language Generation"
authors: [Ginevra Carbone, Gabriele Sarti]
date: 2020-08-26T09:47:38+02:00
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: 2020-08-26T09:47:38+02:00

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["3"]

# Publication name and optional abbreviated publication name.
publication: "ETC-NLG: End-to-end Topic-Conditioned Natural Language Generation"
publication_short: ""

abstract: "Plug-and-play language models (PPLMs) enable topic-conditioned natural language generation by pairing large pre-trained generators with attribute models used to steer the predicted token distribution towards the selected topic. Despite their computational efficiency, PPLMs require large amounts of labeled texts to effectively balance generation fluency and proper conditioning, making them unsuitable for low-resource settings. We present ETC-NLG, an approach leveraging topic modeling annotations to enable fully-unsupervised End-to-end Topic-Conditioned Natural Language Generation over emergent topics in unlabeled document collections. We first test the effectiveness of our approach in a low-resource setting for Italian, evaluating the conditioning for both topic models and gold annotations. We then perform a comparative evaluation of ETC-NLG for Italian and English using a parallel corpus. Finally, we propose an automatic approach to estimate the effectiveness of conditioning on generated utterances."

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
- name: Paper
  url: https://arxiv.org/abs/2008.10875
  icon_pack: fas
  icon: file-contract

url_pdf: 
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