---
# Documentation: https://sourcethemes.com/academic/docs/managing-content/

title: "ICLR 2020 Trends: Better & Faster Transformers for Natural Language Processing"
subtitle: ""
summary: " 
A summary of promising directions from ICLR 2020 for better and faster pretrained tranformers language models.
"
authors: [Gabriele Sarti]
tags: [Natural Language Processing, Language Modeling, Deep Learning, Transformers, ICLR2020, Word Embeddings, Self-Attention]
categories: []
date: 2020-05-03T19:27:36+02:00
lastmod: 2020-05-03T19:27:36+02:00
featured: false
draft: false

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder.
# Focal points: Smart, Center, TopLeft, Top, TopRight, Left, Right, BottomLeft, Bottom, BottomRight.
image:
  caption: ""
  focal_point: ""
  preview_only: false

# Projects (optional).
#   Associate this post with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `projects = ["internal-project"]` references `content/project/deep-learning/index.md`.
#   Otherwise, set `projects = []`.
projects: []
---

[What’s new for Transformers at the ICLR 2020 Conference?](https://towardsdatascience.com/whats-new-for-transformers-at-the-iclr-2020-conference-4285a4294792)




# Self-Attention Variants

### Long-Short Range Attention

*Introduced in*: [Lite Transformer with Long-Short Range Attention](https://openreview.net/forum?id=ByeMPlHKPH) by Wu, Liu et al.

![](assets/lsra.png)

### Tree-Structured Attention

*Introduced in*: [Tree-Structured Attention with Hierarchical Accumulation](https://openreview.net/forum?id=HJxK5pEYvr&noteId=HJxK5pEYvr) by Nguyen et al.

![](assets/hierarchical_accumulation.png)

### Hashed Attention

*Introduced in*: [Reformer: The Efficient Transformer](https://openreview.net/forum?id=rkgNKkHtvB) by Kitaev et al.

![](assets/lsh.png)

### eXtra Hop Attention

*Introduced in*: [Transformer-XH: Multi-Evidence Reasoning with eXtra Hop Attention](https://openreview.net/forum?id=r1eIiCNYwS&noteId=r1eIiCNYwS) by Zhao et al.

![](assets/extra_hop.png)




# Training Objectives

### Discriminative Replacement Task

*Introduced in*: [ELECTRA: Pre-training Text Encoders as Discriminators Rather Than Generators](https://openreview.net/forum?id=r1xMH1BtvB) by Clark et al.

![](assets/electra.png)

### Subtree Masking

*Introduced in*: [Tree-Structured Attention with Hierarchical Accumulation](https://openreview.net/forum?id=HJxK5pEYvr&noteId=HJxK5pEYvr) by Nguyen et al.

![](assets/subtree_masking.png)

### Word and Sentence Structural Tasks

*Introduced in*: [StructBERT: Incorporating Language Structures into Pre-training for Deep Language Understanding](https://openreview.net/forum?id=BJgQ4lSFPH&noteId=BJgQ4lSFPH) by Wang et al.

![](assets/structural_objectives.png)

### Type-Constrained Entity Replacement

*Introduced in*: [Pretrained Encyclopedia: Weakly Supervised Knowledge-Pretrained Language Model](https://openreview.net/forum?id=BJlzm64tDH&noteId=BJlzm64tDH) by Xiong et al.

![](assets/entity_replacement.png)




# Embeddings

### Position-Aware Complex Word Embeddings

*Introduced in*: [Encoding word order in complex embeddings](https://openreview.net/forum?id=Hke-WTVtwr) by Wang et al.

![Complex Word Embeddings](assets/complex_embeddings.png)

### Hierarchical Embeddings

*Introduced in*: [Tree-Structured Attention with Hierarchical Accumulation](https://openreview.net/forum?id=HJxK5pEYvr&noteId=HJxK5pEYvr) by Nguyen et al.

![](assets/hierarchical_embeddings.png)




# Model Architecture

### Compressive Memory

*Introduced in*: [Compressive Transformers for Long-Range Sequence Modelling](https://openreview.net/forum?id=SylKikSYDH&noteId=SylKikSYDH) by Rae et al.

![](assets/compressive_memory.png)

### Reversible Layers

*Introduced in*: [Reformer: The Efficient Transformer](https://openreview.net/forum?id=rkgNKkHtvB) by Kitaev et al.

![](assets/reversible.png)

### Cross-Layer Parameter Sharing

*Introduced in*: [ALBERT: A Lite BERT for Self-supervised Learning of Language Representations](https://openreview.net/forum?id=H1eA7AEtvS) by Lan et al.

![](assets/albert_distances.png)

Also untie hidden layer and word embeddings by projecting embeddings to hidden layer dimension to reduce size in memory.

### Adaptive Depth Estimation

*Introduced in*: [Depth-Adaptive Transformer](https://openreview.net/forum?id=SJg7KhVKPH&noteId=SJg7KhVKPH) by Elbayad et al.

![](assets/depth_adaptive.png)