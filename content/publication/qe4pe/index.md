---
# Documentation: https://sourcethemes.com/academic/docs/managing-content/

title: "QE4PE: Word-level Quality Estimation for Human Post-Editing"
authors: [Gabriele Sarti, Vilém Zouhar, Grzegorz Chrupała, Ana Guerberof Arenas, Malvina Nissim, Arianna Bisazza]
date: 2025-03-06T01:00:00+02:00
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: 2025-03-06T01:00:00+02:00

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["2"]

# Publication name and optional abbreviated publication name.
publication: "Transactions of the Association for Computational Linguistics (2025) 13: 1410–1435."
publication_short: "TACL 2025"

abstract: "Word-level quality estimation (QE) detects erroneous spans in machine translations, which can direct and facilitate human post-editing. While the accuracy of word-level QE systems has been assessed extensively, their usability and downstream influence on the speed, quality and editing choices of human post-editing remain understudied. Our QE4PE study investigates the impact of word-level QE on machine translation (MT) post-editing in a realistic setting involving 42 professional post-editors across two translation directions. We compare four error-span highlight modalities, including supervised and uncertainty-based word-level QE methods, for identifying potential errors in the outputs of a state-of-the-art neural MT model. Post-editing effort and productivity are estimated by behavioral logs, while quality improvements are assessed by word- and segment-level human annotation. We find that domain, language and editors' speed are critical factors in determining highlights' effectiveness, with modest differences between human-made and automated QE highlights underlining a gap between accuracy and usability in professional workflows."

# Summary. An optional shortened abstract.
summary: "We investigate the impact of word-level quality estimation on MT post-editing with 42 professional post-editors."

tags: [Natural Language Processing, Post-editing, Machine Translation, Quality Estimation, Dataset, Behavioral Data, Human Evaluation]
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
  url: https://doi.org/10.1162/TACL.a.46
  icon_pack: fas
  icon: file-alt
- name: ArXiv
  url: https://arxiv.org/abs/2503.03044
  icon_pack: fas
  icon: file-contract
- name: GroTE Demo
  url: https://huggingface.co/spaces/gsarti/grote
  icon_pack: fas
  icon: rocket

url_pdf: https://direct.mit.edu/tacl/article-pdf/doi/10.1162/TACL.a.46/2561722/tacl.a.46.pdf
url_code: https://github.com/gsarti/qe4pe
url_dataset: https://huggingface.co/datasets/gsarti/qe4pe
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