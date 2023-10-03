---
# Documentation: https://wowchemy.com/docs/managing-content/

title: Lightweight fault-localization using multiple coverage types
subtitle: ''
summary: ''
authors:
- Raul Santelices
- James A. Jones
- Yanbing Yu
- Mary Jean Harrold
tags:
- Condition monitoring
- Costs
- Educational institutions
- Informatics
- Instruments
- Isolation technology
- Java
- Performance evaluation
- Runtime
- Software debugging
categories: []
date: '2009-05-01'
lastmod: 2023-09-21T23:26:21-07:00
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
publishDate: '2023-09-22T06:26:21.529673Z'
publication_types:
- '1'
abstract: Lightweight fault-localization techniques use program coverage to isolate
  the parts of the code that are most suspicious of being faulty. In this paper, we
  present the results of a study of three types of program coverage—statements, branches,
  and data dependencies—to compare their effectiveness in localizing faults. The study
  shows that no single coverage type performs best for all faults—different kinds
  of faults are best localized by different coverage types. Based on these results,
  we present a new coverage-based approach to fault localization that leverages the
  unique qualities of each coverage type by combining them. Because data dependencies
  are noticeably more expensive to monitor than branches, we also investigate the
  effects of replacing data-dependence coverage with an approximation inferred from
  branch coverage. Our empirical results show that (1) the cost of fault localization
  using combinations of coverage is less than using any individual coverage type and
  closer to the best case (without knowing in advance which kinds of faults are present),
  and (2) using inferred data-dependence coverage retains most of the benefits of
  combinations.
publication: '*2009 IEEE 31st International Conference on Software Engineering*'
doi: 10.1109/ICSE.2009.5070508
---
