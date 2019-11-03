---
# Documentation: https://sourcethemes.com/academic/docs/managing-content/

title: "Histopathologic Cancer Detection with Neural Networks"
summary: "A journey into the state of the art of histopathologic cancer detection approaches."

authors: [Gabriele Sarti, Leonardo Stincone, Andrea Lorenzon]
tags: [Computer Vision, Capsule Networks, DenseNet, Cancer Detection, Kaggle Competition, DSSC Project]
categories: ["Computer Vision"]

date: 2019-06-28

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder. 
# Focal points: Smart, Center, TopLeft, Top, TopRight, Left, Right, BottomLeft, Bottom, BottomRight.
image:
  caption: ""
  focal_point: ""
  preview_only: false

# Custom links (optional).
#   Uncomment and edit lines below to show custom links.
links:
- name: Code
  url: https://github.com/gsarti/cancer-detection
  icon_pack: fab
  icon: github

# Optional filename of your slides within your talk's folder or a URL.
url_slides: https://drive.google.com/open?id=1N9sFUDGl1dFBXjIF9tjkNHWyg5niH4FN

url_code:
url_pdf: 
url_video:

# Markdown Slides (optional).
#   Associate this talk with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides = "example-slides"` references `content/slides/example-slides.md`.
#   Otherwise, set `slides = ""`.
slides: ""
---

As our final project for the course of Statistical Machine Learning held by Prof. Luca Bortolussi we explored different statistical and deep approaches to the problem of detecting tumors in histopathologic scans. We notably tried a random forest on distributional features extracted by pigment segmentation, a state-of-the-art DenseNet and a Capsule Network with Dynamic Routing.
