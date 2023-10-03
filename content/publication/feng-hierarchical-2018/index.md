---
# Documentation: https://wowchemy.com/docs/managing-content/

title: Hierarchical abstraction of execution traces for program comprehension
subtitle: ''
summary: ''
authors:
- Yang Feng
- Kaj Dreef
- James A. Jones
- Arie van Deursen
tags: []
categories: []
date: '2018-05-01'
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
publishDate: '2023-09-22T06:26:18.380566Z'
publication_types:
- '1'
abstract: Understanding the dynamic behavior of a software system is one of the most
  important and time-consuming tasks for today's software maintainers. In practice,
  understanding the inner workings of software requires studying the source code and
  documentation and inserting logging code in order to map high-level descriptions
  of the program behavior with low-level implementation, i.e., the source code. Unfortunately,
  for large codebases and large log files, such cognitive mapping can be quite challenging.
  To bridge the cognitive gap between the source code and detailed models of program
  behavior, we propose a fully automatic approach to present a semantic abstraction
  with different levels of functional granularity from full execution traces. Our
  approach builds multi-level abstractions and identifies frequent behaviors at each
  level based on a number of execution traces, and then, it labels phases within individual
  execution traces according to the identified major functional behaviors of the system.
  To validate our approach, we conducted a case study on a large-scale subject program,
  Javac, to demonstrate the effectiveness of the mining result. Furthermore, the results
  of a user study demonstrate that our approach is capable of presenting users a high-level
  comprehensible abstraction of execution behavior. Based on a real world subject
  program the participants in our user study were able to achieve a mean accuracy
  of 70%.
publication: '*Proceedings of the 26th Conference on Program Comprehension*'
doi: 10.1145/3196321.3196343
links:
- name: URL
  url: https://doi.org/10.1145/3196321.3196343
---
