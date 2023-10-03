---
# Documentation: https://wowchemy.com/docs/managing-content/

title: Fuzzy Fine-Grained Code-History Analysis
subtitle: ''
summary: ''
authors:
- Francisco Servant
- James A. Jones
tags:
- Analytical models
- Cloning
- Computational modeling
- computer aided software engineering
- Computer bugs
- History
- Measurement
- reasoning about programs
- software engineering
- software maintenance
- Solids
categories: []
date: '2017-05-01'
lastmod: 2023-09-21T23:26:18-07:00
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
publishDate: '2023-09-22T06:26:18.481417Z'
publication_types:
- '1'
abstract: Existing software-history techniques represent source-code evolution as
  an absolute and unambiguous mapping of lines of code in prior revisions to lines
  of code in subsequent revisions. However, the true evolutionary lineage of a line
  of code is often complex, subjective, and ambiguous. As such, existing techniques
  are predisposed to, both, overestimate and underestimate true evolution lineage.
  In this paper, we seek to address these issues by providing a more expressive model
  of code evolution, the fuzzy history graph, by representing code lineage as a continuous
  (i.e., fuzzy) metric rather than a discrete (i.e., absolute) one. Using this more
  descriptive model, we additionally provide a novel multi-revision code-history analysis
  - fuzzy history slicing. In our experiments over three real-world software systems,
  we found that the fuzzy history graph provides a tunable balance of precision and
  recall, and an overall improved accuracy over existing code-evolution models. Furthermore,
  we found that the use of such a fuzzy model of history provided improved accuracy
  for code-history analysis tasks.
publication: '*2017 IEEE/ACM 39th International Conference on Software Engineering
  (ICSE)*'
doi: 10.1109/ICSE.2017.74
---
