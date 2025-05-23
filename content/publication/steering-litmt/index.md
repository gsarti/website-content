---
# Documentation: https://sourcethemes.com/academic/docs/managing-content/

title: "Steering Large Language Models for Machine Translation Personalization"
authors: [Daniel Scalena*, Gabriele Sarti*, Arianna Bisazza, Elisabetta Fersini, Malvina Nissim]
date: 2025-05-23T00:00:00+02:00
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: 2023-05-29T09:47:38+02:00

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["3"]

# Publication name and optional abbreviated publication name.
publication: "Arxiv Preprint"
publication_short: "Arxiv"

abstract: "High-quality machine translation systems based on large language models (LLMs) have simplified the production of personalized translations reflecting specific stylistic constraints. However, these systems still struggle in settings where stylistic requirements are less explicit and might be harder to convey via prompting. We explore various strategies for personalizing LLM-generated translations in low-resource settings, focusing on the challenging literary translation domain. We explore prompting strategies and inference-time interventions for steering model generations towards a personalized style, and propose a contrastive framework exploiting latent concepts extracted from sparse autoencoders to identify salient personalization properties. Our results show that steering achieves strong personalization while preserving translation quality. We further examine the impact of steering on LLM representations, finding model layers with a relevant impact for personalization are impacted similarly by multi-shot prompting and our steering method, suggesting similar mechanism at play."

# Summary. An optional shortened abstract.
summary: "We evaluate prompting and steering based methods for machine translation personalization in the literary domain."

tags: [Natural Language Processing, Deep Learning, Machine Translation, Style Transfer, Multilingual, Prompting, Steering, Interpretability, Large Language Models]
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
  url: https://arxiv.org/abs/2505.16612
  icon_pack: fas
  icon: file-contract

url_pdf: https://arxiv.org/pdf/2505.16612
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