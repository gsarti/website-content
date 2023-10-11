---
# Documentation: https://sourcethemes.com/academic/docs/managing-content/

title: "DecoderLens: Layerwise Interpretation of Encoder-Decoder Transformers"
authors: [Anna Langedijk, Hosein Mohebbi, Gabriele Sarti, Willem Zuidema, Jaap Jumelet]
date: 2023-10-05T00:00:00+02:00
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: 2023-10-05T00:00:00+02:00

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["3"]

# Publication name and optional abbreviated publication name.
publication: "Arxiv Preprint"
publication_short: "Arxiv"

abstract: "In recent years, many interpretability methods have been proposed to help interpret the internal states of Transformer-models, at different levels of precision and complexity. Here, to analyze encoder-decoder Transformers, we propose a simple, new method: DecoderLens. Inspired by the LogitLens (for decoder-only Transformers), this method involves allowing the decoder to cross-attend representations of intermediate encoder layers instead of using the final encoder output, as is normally done in encoder-decoder models. The method thus maps previously uninterpretable vector representations to human-interpretable sequences of words or symbols. We report results from the DecoderLens applied to models trained on question answering, logical reasoning, speech recognition and machine translation. The DecoderLens reveals several specific subtasks that are solved at low or intermediate layers, shedding new light on the information flow inside the encoder component of this important class of models. "

# Summary. An optional shortened abstract.
summary: "We propose DecoderLens, a method to evaluate the iterative refinement of representations in encoder-decoder Transformer models."

tags: [Natural Language Processing, Deep Learning, Interpretability, Machine Translation, Automatic Speech Recognition, Question Answering, Logical Reasoning]
categories: [Natural Language Processing]
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
  url: https://arxiv.org/abs/2310.03686
  icon_pack: fas
  icon: file-contract
- name: Hugging Face
  url: https://huggingface.co/papers/2310.03686
  icon: codepen
  icon_pack: fab

url_pdf: https://arxiv.org/pdf/2310.03686.pdf
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