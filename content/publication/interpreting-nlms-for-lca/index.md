---
# Documentation: https://sourcethemes.com/academic/docs/managing-content/

title: "Interpreting Neural Language Models for Linguistic Complexity Assessment"
authors: [Gabriele Sarti]
date: 2020-12-19T09:47:38+02:00
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: 2020-08-26T09:47:38+02:00

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["7"]

# Publication name and optional abbreviated publication name.
publication: "MSc Thesis in Data Science and Scientific Computing at the University of Trieste"
publication_short: "MSc Thesis @ UniTrieste"

abstract: "The study of linguistic complexity is a deeply multidisciplinary area, ranging from the study of cognitive processing in human readers to the classification of structural complexity characterizing expressions in natural language. In recent times, the use of computational methods for the processing and analysis of language has produced important developments in the understanding of multiple phenomena associated with linguistic complexity. In line with the state of the art in the sector, this thesis presents a model-driven study of multiple phenomena associated with linguistic complexity. First, relationships subsisting between various extrinsic complexity metrics - perception of linguistic complexity, readability, cognitive processing and predictability - are empirically explored, highlighting similarities and differences from a linguistically and cognitively motivated perspective. Then, it is studied how the information underlying the different complexity metrics can be acquired by language models based on neural networks, at various levels of abstraction and granularity, using interpretability techniques derived from the literature on natural language processing. In conclusion, the ability of various computational models of complexity in predicting cognitive processing difficulties associated with atypical syntactic constructs, such as garden-path sentences, is evaluated. The experimental results of this study provide convergent evidence regarding the limited abstraction and generalization abilities of state-of-the-art neural language models for the prediction of linguistic complexity, and encourage the adoption of lines of research that integrate symbolic and interpretable information in this sector. Code is available at https://github.com/gsarti/interpreting-complexity"

# Summary. An optional shortened abstract.
summary: "This thesis presents a model-driven study of multiple phenomena associated with linguistic complexity, and how those get encoded by neural language models' learned representations."

tags: [Natural Language Processing, Deep Learning, Interpretability, Language Modeling, Transformers, Canonical Correlation Analysis, Garden-path Sentences, Probing Tasks, Representational Similarity Analysis, SyntaxGym, Surprisal, Eye-tracking]
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
- name: Gitbook
  url: ../thesis/introduction.html
  icon_pack: fas
  icon: file-contract

url_pdf: ../thesis/Sarti_2020_Interpreting_NLMs_for_LCA.pdf
url_code: https://github.com/gsarti/interpreting-complexity
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