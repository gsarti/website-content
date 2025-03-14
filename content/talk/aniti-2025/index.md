---
# Documentation: https://sourcethemes.com/academic/docs/managing-content/

title: "Interpreting Context Usage in Generative Language Models"
event: ANITI Seminar
event_url:
location:  IRT Saint Exupéry, Toulouse, France
address:
  street:
  city: Tolouse
  region: Occitanie
  postcode:
  country: France
summary: "This presentation focuses on applying post-hoc interpretability techniques to analyze how language models (LMs) use input information throughout the generation process. We briefly introduce Inseq, our open-source toolkit designed to simplify advanced feature attribution analyses for LMs. Then, our Plausibility Evaluation of Context Reliance (PECoRe) interpretability framework is introduced to conduct data-driven analyses of context usage in LMs. In conclusion, we showcase how PECoRe can easily be adapted to retrieval-augmented generation (RAG) settings to produce internals-based citations for model answers. Our proposed Model Internals for RAG Explanations (MIRAGE) method achieves citation quality comparable to supervised answer validators with no additional training, producing citations that are faithful to actual context usage during generation."

# Talk start and end times.
#   End time can optionally be hidden by prefixing the line with `#`.
date: 2025-03-11T14:00:00+01:00
#date_end: 2019-10-27T17:59:41+01:00
all_day: true

# Schedule page publish date (NOT talk date).
publishDate: 2024-07-15

authors: [Gabriele Sarti]
tags: [Natural Language Processing, Interpretability, Sequence-to-sequence, Language Modeling, Feature Attribution, Retrieval-augmented Generation]
categories: ["Natural Language Processing", "Academic"]

# Is this a featured talk? (true/false)
featured: false

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder. 
# Focal points: Smart, Center, TopLeft, Top, TopRight, Left, Right, BottomLeft, Bottom, BottomRight.
image:
  caption: ""
  focal_point: ""
  preview_only: false

# Custom links (optional).
#   Uncomment and edit lines below to show custom links.
# links:
# - name: Follow
#   url: https://twitter.com
#   icon_pack: fab
#   icon: twitter

# Optional filename of your slides within your talk's folder or a URL.
url_slides: https://docs.google.com/presentation/d/1wgD3q19ECrqt8j59Mn4h4fpdti_YeJMFolzt84ewFwk/edit?usp=sharing

url_code: https://github.com/inseq-team/inseq
url_pdf:
url_video:

# Markdown Slides (optional).
#   Associate this talk with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides = "example-slides"` references `content/slides/example-slides.md`.
#   Otherwise, set `slides = ""`.
slides: ""

# Projects (optional).
#   Associate this post with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `projects = ["internal-project"]` references `content/project/deep-learning/index.md`.
#   Otherwise, set `projects = []`.
projects: ["inseq", "pecore"]
---
