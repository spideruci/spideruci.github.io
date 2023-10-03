---
# Documentation: https://wowchemy.com/docs/managing-content/

title: Fault interaction and its repercussions
subtitle: ''
summary: ''
authors:
- Nicholas DiGiuseppe
- James A. Jones
tags:
- Flexible printed circuits
- Informatics
- Interference
- Noise
- Schedules
- Software
- Testing
categories: []
date: '2011-09-01'
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
publishDate: '2023-09-22T06:26:20.713074Z'
publication_types:
- '1'
abstract: Multiple faults in a program can interact to form new behaviors in a program
  that would not be realized if the program were to contain the individual faults.
  This paper presents an in-depth study of the effects of the interaction of faults
  within a program. Many researchers attempt to ameliorate the effects of faulty programs.
  Unfortunately, such researchers are left to rely upon intuition about fault behavior
  due to the paucity of formalized studies of faults and their behavior. In an attempt
  to advance the understanding of faults and their behavior, we conducted a study
  of fault interaction across six subjects with more than 65,000 multiple-fault versions.
  The results of our study show four significant types of interaction, with one type
  - faults obscuring the effects of other faults - as the most prevalent type. The
  prevalence of obscuring faults' effects has an adverse effect on many automated
  software-engineering techniques, such as regression-testing, fault-localization,
  and fault-clustering techniques. Given that software commonly contains more than
  a single fault, these results have implications for developers and researchers alike
  by informing them of expected complications, which in many instances are opposite
  to intuition.
publication: '*2011 27th IEEE International Conference on Software Maintenance (ICSM)*'
doi: 10.1109/ICSM.2011.6080767
---
