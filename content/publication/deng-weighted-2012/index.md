---
# Documentation: https://wowchemy.com/docs/managing-content/

title: Weighted System Dependence Graph
subtitle: ''
summary: ''
authors:
- Fang Deng
- James A. Jones
tags:
- Analytical models
- Context
- Correlation
- Data models
- debugging
- Debugging
- dynamic analysis
- fault-localization
- hybrid analysis
- Instruments
- program models
- Runtime
- static analysis
categories: []
date: '2012-04-01'
lastmod: 2023-09-21T23:26:20-07:00
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
publishDate: '2023-09-22T06:26:20.010700Z'
publication_types:
- '1'
abstract: In this paper, we present a weighted, hybrid program-dependence model that
  represents the relevance of highly related, dependent code to assist developer comprehension
  of the program for multiple software-engineering tasks. Programmers often need to
  understand the dependencies among program elements, which may exist across multiple
  modules. Although such dependencies can be gathered from traditional models, such
  as slices, the scalability of these approaches is often prohibitive for direct,
  practical use. To address this scalability issue, as well as to assist developer
  comprehension, we introduce a program model that includes static dependencies as
  well as information about any number of executions, which inform the weight and
  relevance of the dependencies. Additionally, classes of executions can be differentiated
  in such a way as to support multiple software-engineering tasks. We evaluate this
  weighted, hybrid model for a task that involves exploring the structural context
  while debugging. The results demonstrate that the new model more effectively reveals
  relevant failure-correlated code than the static-only model, thus enabling a more
  scalable exploration or post hoc analysis.
publication: '*Verification and Validation 2012 IEEE Fifth International Conference
  on Software Testing*'
doi: 10.1109/ICST.2012.118
---
