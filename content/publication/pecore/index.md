---
# Documentation: https://sourcethemes.com/academic/docs/managing-content/

title: "Quantifying the Plausibility of Context Reliance in Neural Machine Translation"
authors: [Gabriele Sarti, Grzegorz Chrupała, Malvina Nissim, Arianna Bisazza]
date: 2023-10-02T00:00:00+02:00
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: 2023-10-02T00:00:00+02:00

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["3"]

# Publication name and optional abbreviated publication name.
publication: "Arxiv Preprint"
publication_short: "Arxiv"

abstract: "Establishing whether language models can use contextual information in a human-plausible way is important to ensure their safe adoption in real-world settings. However, the questions of when and which parts of the context affect model generations are typically tackled separately, and current plausibility evaluations are practically limited to a handful of artificial benchmarks. To address this, we introduce Plausibility Evaluation of Context Reliance (PECoRe), an end-to-end interpretability framework designed to quantify context usage in language models' generations. Our approach leverages model internals to (i) contrastively identify context-sensitive target tokens in generated texts and (ii) link them to contextual cues justifying their prediction. We use PECoRe to quantify the plausibility of context-aware machine translation models, comparing model rationales with human annotations across several discourse-level phenomena. Finally, we apply our method to unannotated generations to identify context-mediated predictions and highlight instances of (im)plausible context usage in model translations. "

# Summary. An optional shortened abstract.
summary: "We introduce PECoRe, an interpretability framework for identifying context dependence in language model generations."

tags: [Natural Language Processing, Deep Learning, Interpretability, Machine Translation, Feature Attribution, Context Usage]
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
  url: https://arxiv.org/abs/2310.01188
  icon_pack: fas
  icon: file-contract
- name: Hugging Face
  url: https://huggingface.co/papers/2310.01188
  icon: codepen
  icon_pack: fab

url_pdf: https://arxiv.org/pdf/2310.01188.pdf
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