---
# Documentation: https://wowchemy.com/docs/managing-content/

title: An Empirical Study on Software Failure Classification with Multi-label and
  Problem-Transformation Techniques
subtitle: ''
summary: ''
authors:
- Yang Feng
- James Jones
- Zhenyu Chen
- Chunrong Fang
tags:
- Computer crashes
- Empirical Study
- Failure Classification
- Machine learning
- Maintenance engineering
- multi-label classification
- Software
- Task analysis
- Training
- Training data
categories: []
date: '2018-04-01'
lastmod: 2023-09-05T01:57:09-07:00
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
publishDate: '2023-09-05T08:56:33.724536Z'
publication_types:
- '1'
abstract: 'Classification techniques have been used in software-engineering research
  to perform tasks such as categorizing software executions. Traditionally, existing
  work has proposed single-label failure classification techniques, in which the training
  and subsequent executions are labeled with a singular fault attribution. Although
  such approaches have received substantial attention in research on automated software
  engineering, in reality, recent work shows that the assumption of such a single
  attribution is often unrealistic: in practice, the inherent characteristics of software
  behavior, such as multiple faults that contribute to failures and fault interactions,
  may negatively influence the effectiveness of these techniques. To relax this unrealistic
  assumption, in the machine learning field, researchers have proposed new approaches
  for multi-label classification. However, the effectiveness and efficiency of such
  approaches varies widely based upon application domains. In this paper, we empirically
  investigate the performance of these new approaches on the failure classification
  task under different application settings. We conducted experiments using eight
  classification techniques on five subject programs with more than 8,000 faulty versions
  to investigate how each such technique accounts for the intricacies of software
  behavior. Our experimental results show that multi-label techniques provide improved
  accuracy over single-label. We also evaluated the efficiency of the training and
  prediction phases of each technique, and offer guidance as to the applicability
  for each technique for different usage contexts.'
publication: '*2018 IEEE 11th International Conference on Software Testing, Verification
  and Validation (ICST)*'
doi: 10.1109/ICST.2018.00039
---
