---
# Documentation: https://sourcethemes.com/academic/docs/managing-content/

title: "Unsupervised Word-level Quality Estimation for Machine Translation Through the Lens of Annotators (Dis)agreement"
authors: [Gabriele Sarti, Vilém Zouhar, Malvina Nissim, Arianna Bisazza]
date: 2025-05-30T01:00:00+02:00
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: 2025-06-01T01:00:00+02:00

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["3"]

# Publication name and optional abbreviated publication name.
publication: "Arxiv Preprint"
publication_short: "Arxiv"

abstract: "Word-level quality estimation (WQE) aims to automatically identify fine-grained error spans in machine-translated outputs and has found many uses, including assisting translators during post-editing. Modern WQE techniques are often expensive, involving prompting of large language models or ad-hoc training on large amounts of human-labeled data. In this work, we investigate efficient alternatives exploiting recent advances in language model interpretability and uncertainty quantification to identify translation errors from the inner workings of translation models. In our evaluation spanning 14 metrics across 12 translation directions, we quantify the impact of human label variation on metric performance by using multiple sets of human labels. Our results highlight the untapped potential of unsupervised metrics, the shortcomings of supervised methods when faced with label uncertainty, and the brittleness of single-annotator evaluation practices."

# Summary. An optional shortened abstract.
summary: "We evaluate unsupervised word-level quality estimation (WQE) methods for machine translation, focusing on their robustness to human label variation."

tags: [Natural Language Processing, Machine Translation, Quality Estimation, Human Label Variation, Uncertainty Quantification, Interpretability]
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
  url: https://arxiv.org/abs/2505.23183
  icon_pack: fas
  icon: file-contract

url_pdf: https://arxiv.org/pdf/2505.23183
url_code: https://github.com/gsarti/labl/tree/main/examples/unsup_wqe
url_dataset: https://huggingface.co/datasets/gsarti/unsup_wqe_metrics
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