---
# Documentation: https://sourcethemes.com/academic/docs/managing-content/

title: "Non Verbis, Sed Rebus: Large Language Models are Weak Solvers of Italian Rebuses"
authors: [Gabriele Sarti, Tommaso Caselli, Arianna Bisazza, Malvina Nissim]
date: 2024-08-02T01:00:00+02:00
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: 2024-08-02T01:00:00+02:00

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["1"]

# Publication name and optional abbreviated publication name.
publication: "Proceedings of the 10th Italian Conference on Computational Linguistics"
publication_short: "CLiC-it 2024"

abstract: "Rebuses are puzzles requiring constrained multi-step reasoning to identify a hidden phrase from a set of images and letters. In this work, we introduce a large collection of verbalized rebuses for the Italian language and use it to assess the rebus-solving capabilities of state-of-the-art large language models. While general-purpose systems such as LLaMA-3 and GPT-4o perform poorly on this task, ad-hoc fine-tuning seems to improve models' performance. However, we find that performance gains from training are largely motivated by memorization. Our results suggest that rebus solving remains a challenging test bed to evaluate large language models' linguistic proficiency and sequential instruction-following skills."

# Summary. An optional shortened abstract.
summary: "We evaluate the rebus-solving capabilities of large language models on a new Italian dataset."

tags: [Natural Language Processing, HuggingFace, Italian, Large Language Models, Evaluation, Word Games, Rebus]
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
  url: https://arxiv.org/abs/2408.00584
  icon_pack: fas
  icon: file-contract
- name: CALAMITA Challenge
  url: https://ceur-ws.org/Vol-3878/132_calamita_long.pdf
  icon_pack: fas
  icon: magnet
- name: Models & Dataset
  url: https://huggingface.co/collections/gsarti/verbalized-rebus-clic-it-2024-66ab8f11cb04e68bdf4fb028
  icon: codepen
  icon_pack: fab
- name: Repository
  url: https://github.com/gsarti/verbalized-rebus
  icon_pack: fab
  icon: github
- name: Demo
  url: https://huggingface.co/spaces/gsarti/verbalized-rebus-solver
  icon_pack: fas
  icon: rocket

url_pdf: https://arxiv.org/pdf/2408.00584.pdf
url_code: 
url_dataset: https://huggingface.co/datasets/gsarti/eureka-rebus
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