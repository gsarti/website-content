---
# Documentation: https://sourcethemes.com/academic/docs/managing-content/

title: "Interpreting Context Usage in Generative Language Models with Inseq and PECoRe"
event: Politecnico di Torino Invited Talk
event_url:
location: Online
address:
  street:
  city: Turin
  region: Piedmont
  postcode:
  country: Italy
summary: "This talk discusses the challenges and opportunities in conducting interpretability analyses of generative language models. We begin by presenting Inseq, an open-source toolkit for advanced feature attribution analyses of language models. The usage of Inseq is illustrated through examples of state-of-the-art approaches contrastive attribution, input dependence and locating factual knowledge in intermediate model representations. Then, we introduce Plausibility Evaluation of Context Reliance (PECoRe), an end-to-end interpretability framework using model internals  to detect context-dependent spans in model generations and trace their prediction back to salient tokens in the available context. The usage of PECoRe is showcased on various generative tasks, including machine translation, story generation and retrieval-augmented question answering."

# Talk start and end times.
#   End time can optionally be hidden by prefixing the line with `#`.
date: 2024-05-20T9:00:00+01:00
#date_end: 2019-10-27T17:59:41+01:00
all_day: true

# Schedule page publish date (NOT talk date).
publishDate: 2024-02-26

authors: [Gabriele Sarti]
tags: [Natural Language Processing, Interpretability, Sequence-to-sequence, Language Modeling, Feature Attribution]
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
url_slides: https://docs.google.com/presentation/d/1NYjoq9kvYs7Rr233Ys1YPZhCRzCLwHO3KIAMElYsqkY/edit#slide=id.p

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
