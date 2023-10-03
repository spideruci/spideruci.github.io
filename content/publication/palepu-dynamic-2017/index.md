---
# Documentation: https://wowchemy.com/docs/managing-content/

title: Dynamic Dependence Summaries
subtitle: ''
summary: ''
authors:
- Vijay Krishna Palepu
- Guoqing Xu
- James A. Jones
tags:
- dependence analysis
- Dynamic analysis
- dynamic slicing
- summaries
categories: []
date: '2017-01-01'
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
publishDate: '2023-09-22T06:26:18.582972Z'
publication_types:
- '2'
abstract: Software engineers construct modern-day software applications by building
  on existing software libraries and components that they necessarily do not author
  themselves. Thus, contemporary software applications rely heavily on existing standard
  and third-party libraries for their execution and behavior. As such, effective runtime
  analysis of such a software application’s behavior is met with new challenges. To
  perform dynamic analysis of a software application, all transitively dependent external
  libraries must also be monitored and analyzed at each layer of the software application’s
  call stack. However, monitoring and analyzing large and often numerous external
  libraries may prove to be prohibitively expensive. Moreover, an overabundance of
  library-level analyses may obfuscate the details of the actual software application’s
  dynamic behavior. In other words, the extensive use of existing libraries by a software
  application renders the results of its dynamic analysis both expensive to compute
  and difficult to understand. We model software component behavior as dynamically
  observed data- and control dependencies between inputs and outputs of a software
  component. Such data- and control dependencies are monitored at a fine-grain instruction-level
  and are collected as dynamic execution traces for software runs. As an approach
  to address the complexities and expenses associated with analyzing dynamically observable
  behavior of software components, we summarize and reuse the data- and control dependencies
  between the inputs and outputs of software components. Dynamically monitored data-
  and control dependencies, between the inputs and outputs of software components,
  upon summarization are called dynamic dependence summaries. Software components,
  equipped with dynamic dependence summaries, afford the omission of their exhaustive
  runtime analysis. Nonetheless, the reuse of dependence summaries would necessitate
  the abstraction of any concrete runtime information enclosed within the summary,
  thus potentially causing a loss in the information modeled by the dependence summary.
  Therefore, benefits to the efficiency of dynamic analyses that use such summarization
  may be afforded with losses of accuracy. As such, we evaluate the potential accuracy
  loss and the potential performance gain with the use of dynamic dependence summaries.
  Our results show, on average, a 13× speedup with the use of dynamic dependence summaries,
  with an accuracy of 90% in a real-world software engineering task.
publication: '*ACM Transactions on Software Engineering and Methodology*'
doi: 10.1145/2968444
links:
- name: URL
  url: https://dl.acm.org/doi/10.1145/2968444
---
