---
# Documentation: https://wowchemy.com/docs/managing-content/

title: 'History slicing: assisting code-evolution tasks'
subtitle: ''
summary: ''
authors:
- Francisco Servant
- James A. Jones
tags:
- mining software repositories
- program comprehension
- software evolution
- software visualization
categories: []
date: '2012-11-01'
lastmod: 2023-09-21T23:26:19-07:00
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
publishDate: '2023-09-22T06:26:19.605433Z'
publication_types:
- '1'
abstract: "Many software-engineering tasks require developers to understand the history\
  \ and evolution of source code. However, today's software-development techniques\
  \ and tools are not well suited for the easy and efficient procurement of such information.\
  \ In this paper, we present an approach called history slicing that can automatically\
  \ identify a minimal number of code modifications, across any number of revisions,\
  \ for any arbitrary segment of source code at fine granularity. We also present\
  \ our implementation of history slicing, Chronos, that includes a novel visualization\
  \ of the entire evolution for the code of interest. We provide two experiments:\
  \ one experiment automatically computes 16,000 history slices to determine the benefit\
  \ brought by various levels of automation, and another experiment that assesses\
  \ the practical implications of history slicing for actual developers using the\
  \ technique for actual software-maintenance tasks that involve code evolution. The\
  \ experiments show that history slicing offered drastic improvements over the conventional\
  \ techniques in three ways: (1) the amount of information needed to be examined\
  \ and traced by developers was reduced by up to three orders of magnitude; (2) the\
  \ correctness of developers attempting to solve software-maintenance tasks was more\
  \ than doubled; and (3) the time to completion of these software-maintenance tasks\
  \ was almost halved."
publication: '*Proceedings of the ACM SIGSOFT 20th International Symposium on the
  Foundations of Software Engineering*'
doi: 10.1145/2393596.2393646
links:
- name: URL
  url: https://doi.org/10.1145/2393596.2393646
---
