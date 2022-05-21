---
# Documentation: https://wowchemy.com/docs/managing-content/

title: 'Qunity: A Unified Language for Quantum and Classical Computing'
subtitle: ''
summary: ''
authors:
- Finn Voichick
- Robert Rand
- Michael Hicks
tags: []
categories: []
date: '2022-01-01'
lastmod: 2022-05-19T22:28:50-05:00
featured: false
draft: false

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder.
# Focal points: Smart, Center, TopLeft, Top, TopRight, Left, Right, BottomLeft, Bottom, BottomRight.
image:
  caption: ''
  focal_point: ''
  preview_only: false

# Projects (optional).
#   Associate this post with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `projects = ["internal-project"]` references `content/project/deep-learning/index.md`.
#   Otherwise, set `projects = []`.
projects: []
publishDate: '2022-05-21T11:48:47.986349Z'
publication_types:
- '3'
abstract: We introduce Qunity, a new quantum programming language designed around
  the central goal of treating quantum computing as a natural generalization of classical
  computing. Qunity presents a unified syntax where familiar programming constructs
  can have both quantum and classical effects. For example, one can use sum types
  to implement the direct sum of linear operators, exception handling syntax to implement
  projective measurements, and aliasing to induce entanglement. Further, Qunity takes
  advantage of the overlooked BQP subroutine theorem, allowing one to construct reversible
  subroutines from irreversible quantum algorithms through the uncomputation of \"garbage\"
  outputs. Unlike existing languages that enable quantum aspects with a separate add-on
  (e.g., gates added to a classical language), we unify quantum and classical computing
  through novel compositional semantics based on Kraus operators. We present Qunity's
  syntax, type system, and denotational semantics, showing how it can cleanly express
  several quantum algorithms. We also outline how Qunity could be compiled to OpenQASM,
  demonstrating the realizability of our design.
publication: ''
doi: arxiv.2204.12384
links:
- name: arXiv
  url: https://arxiv.org/abs/2204.12384
- name: URL
  url: https://arxiv.org/abs/2204.12384
---
