---
# Documentation: https://sourcethemes.com/academic/docs/managing-content/

title: "Model Internals-based Answer Attribution for Trustworthy Retrieval-Augmented Generation"
authors: [Jirui Qi*, Gabriele Sarti*, Raquel Fernández, Arianna Bisazza]
date: 2024-06-15T00:00:00+02:00
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: 2024-06-15T00:00:00+02:00

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["3"]

# Publication name and optional abbreviated publication name.
publication: "Arxiv Preprint"
publication_short: "Arxiv"
comment: "* Equal contribution"

abstract: "Ensuring the verifiability of model answers is a fundamental challenge for retrieval-augmented generation (RAG) in the question answering (QA) domain. Recently, self-citation prompting was proposed to make large language models (LLMs) generate citations to supporting documents along with their answers. However, self-citing LLMs often struggle to match the required format, refer to non-existent sources, and fail to faithfully reflect LLMs' context usage throughout the generation. In this work, we present MIRAGE --Model Internals-based RAG Explanations -- a plug-and-play approach using model internals for faithful answer attribution in RAG applications. MIRAGE detects context-sensitive answer tokens and pairs them with retrieved documents contributing to their prediction via saliency methods. We evaluate our proposed approach on a multilingual extractive QA dataset, finding high agreement with human answer attribution. On open-ended QA, MIRAGE achieves citation quality and efficiency comparable to self-citation while also allowing for a finer-grained control of attribution parameters. Our qualitative evaluation highlights the faithfulness of MIRAGE's attributions and underscores the promising application of model internals for RAG answer attribution."

# Summary. An optional shortened abstract.
summary: "MIRAGE uses model internals for faithful answer attribution in retrieval-augmented generation applications."

tags: [Natural Language Processing, Deep Learning, Interpretability, Question Answering, Feature Attribution, Context Usage, Retrieval-Augmented Generation]
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
  url: https://arxiv.org/abs/2406.13663
  icon_pack: fas
  icon: file-contract
- name: Demo
  url: https://huggingface.co/spaces/gsarti/mirage
  icon_pack: fas
  icon: rocket
- name: Repository
  url: https://github.com/Betswish/MIRAGE
  icon_pack: fab
  icon: github

url_pdf: https://arxiv.org/pdf/2406.13663.pdf
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
projects: ["pecore"]

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
slides: ""
---