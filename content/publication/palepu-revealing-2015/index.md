---
# Documentation: https://wowchemy.com/docs/managing-content/

title: Revealing runtime features and constituent behaviors within software
subtitle: ''
summary: ''
authors:
- Vijay Krishna Palepu
- James A. Jones
tags:
- Brain
- Data visualization
- Image color analysis
- Layout
- Runtime
- Software
- Visualization
categories: []
date: '2015-09-01'
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
publishDate: '2023-09-22T06:26:18.888800Z'
publication_types:
- '1'
abstract: 'Software engineers organize source code into a dominant hierarchy of components
  and modules that may emphasize various characteristics over runtime behavior. In
  this way, runtime features may involve cross-cutting aspects of code from multiple
  components, and some of these features may be emergent in nature, rather than designed.
  Although source-code modularization assists software engineers to organize and find
  components, identifying such cross-cutting feature sets can be more difficult. This
  work presents a visualization that includes a static (i.e., compile-time) representation
  of source code that gives prominence to clusters of cooperating source-code instructions
  to identify dynamic (i.e., runtime) features and constituent behaviors within executions
  of the software. In addition, the visualization animates software executions to
  reveal which feature clusters are executed and in what order. The result has revealed
  the principal behaviors of software executions, and those behaviors were revealed
  to be (in some cases) cohesive, modular source-code structures and (in other cases)
  cross-cutting, emergent behaviors that involve multiple modules. In this paper,
  we describe our system (CEREBRO), envisage the uses to which it can be put, and
  evaluate its ability to reveal emergent runtime features and internal constituent
  behaviors of execution. We found that: (1) the visualization revealed emergent and
  commonly occuring functionalities that cross-cut the structural decomposition of
  the system; (2) four independent judges generally agreed in their interpretations
  of the code clusters, especially when informed only by our visualization; and (3)
  interacting with the external interface of an application while simultaneously observing
  the internal execution facilitated localization of code that implements the features
  and functionality evoked externally.'
publication: '*2015 IEEE 3rd Working Conference on Software Visualization (VISSOFT)*'
doi: 10.1109/VISSOFT.2015.7332418
---
