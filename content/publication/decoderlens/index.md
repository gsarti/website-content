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
publication_types: ["1"]

# Publication name and optional abbreviated publication name.
publication: "Findings of the Association for Computational Linguistics: NAACL 2024"
publication_short: "Findings of NAACL 2024"

abstract: "In recent years, several interpretability methods have been proposed to interpret the inner workings of Transformer models at different levels of precision and complexity.In this work, we propose a simple but effective technique to analyze encoder-decoder Transformers. Our method, which we name DecoderLens, allows the decoder to cross-attend representations of intermediate encoder activations instead of using the default final encoder output.The method thus maps uninterpretable intermediate vector representations to human-interpretable sequences of words or symbols, shedding new light on the information flow in this popular but understudied class of models.We apply DecoderLens to question answering, logical reasoning, speech recognition and machine translation models, finding that simpler subtasks are solved with high precision by low and intermediate encoder layers."

# Summary. An optional shortened abstract.
summary: "We propose DecoderLens, a method to interpret the iterative refinement of representations in encoder-decoder Transformer models."

tags: [Natural Language Processing, Deep Learning, Interpretability, Machine Translation, Automatic Speech Recognition, Factual Knowledge, Logical Reasoning]
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
- name: Paper
  url: https://aclanthology.org/2024.findings-naacl.296/
  icon_pack: fas
  icon: file-alt
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