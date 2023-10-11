---
# Documentation: https://sourcethemes.com/academic/docs/managing-content/

title: "RAMP: Retrieval and Attribute-Marking Enhanced Prompting for Attribute-Controlled Translation"
authors: [Gabriele Sarti, Phu Mon Htut, Xing Niu, Benjamin Hsu, Anna Currey, Georgiana Dinu, Maria Nadejde]
date: 2023-05-29T09:47:38+02:00
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: 2023-05-29T09:47:38+02:00

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["1"]

# Publication name and optional abbreviated publication name.
publication: "In Proceedings of the 61st Annual Meeting of the Association for Computational Linguistics: Main Conference Track"
publication_short: "ACL 2023"

abstract: "Attribute-controlled translation (ACT) is a subtask of machine translation that involves controlling stylistic or linguistic attributes (like formality and gender) of translation outputs. While ACT has garnered attention in recent years due to its usefulness in real-world applications, progress in the task is currently limited by dataset availability, since most prior approaches rely on supervised methods. To address this limitation, we propose Retrieval and Attribute-Marking enhanced Prompting (RAMP), which leverages large multilingual language models to perform ACT in few-shot and zero-shot settings. RAMP improves generation accuracy over the standard prompting approach by (1) incorporating a semantic similarity retrieval component for selecting similar in-context examples, and (2) marking in-context examples with attribute annotations. Our comprehensive experiments show that RAMP is a viable approach in both zero-shot and few-shot settings. "

# Summary. An optional shortened abstract.
summary: "We introduce Retrieval and Attribute-Marking enhanced Prompting (RAMP) to perform attribute-controlled MT with multilingual LLMs."

tags: [Natural Language Processing, Deep Learning, Machine Translation, Style Transfer, Multilingual, Prompting, Large Language Models]
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
- name: Paper
  url: https://aclanthology.org/2023.acl-short.126/
  icon_pack: fas
  icon: file-alt
- name: ArXiv
  url: https://arxiv.org/abs/2305.17131
  icon_pack: fas
  icon: file-contract

url_pdf: https://aclanthology.org/2023.acl-short.126.pdf
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