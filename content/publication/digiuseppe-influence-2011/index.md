---
# Documentation: https://wowchemy.com/docs/managing-content/

title: On the influence of multiple faults on coverage-based fault localization
subtitle: ''
summary: ''
authors:
- Nicholas DiGiuseppe
- James A. Jones
tags:
- debugging
- empirical studies
- fault localization
categories: []
date: '2011-07-01'
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
publishDate: '2023-09-22T06:26:20.920960Z'
publication_types:
- '1'
abstract: This paper presents an empirical study on the effects of the quantity of
  faults on statistical, coverage-based fault localization techniques. The former
  belief was that the effectiveness of fault-localization techniques was inversely
  proportional to the quantity of faults. In an attempt to verify these beliefs, we
  conducted a study on three programs varying in size on more than 13,000 multiple-fault
  versions. We found that the influence of multiple faults (1) was not as great as
  expected, (2) created a negligible effect on the effectiveness of the fault localization,
  and (3) was often even complimentary to the fault-localization effectiveness. In
  general, even in the presence of many faults, at least one fault was found by the
  fault-localization technique with high effectiveness. We also found that some faults
  were localizable regardless of the presence of other faults, whereas other faults'
  ability to be found by these techniques varied greatly in the presence of other
  faults. Because almost all real-world software contains multiple faults, these results
  impact the use of statistical fault-localization techniques and provide a greater
  understanding of their potential in practice.
publication: '*Proceedings of the 2011 International Symposium on Software Testing
  and Analysis*'
doi: 10.1145/2001420.2001446
links:
- name: URL
  url: https://doi.org/10.1145/2001420.2001446
---
