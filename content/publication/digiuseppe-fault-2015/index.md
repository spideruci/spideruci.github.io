---
# Documentation: https://wowchemy.com/docs/managing-content/

title: Fault density, fault types, and spectra-based fault localization
subtitle: ''
summary: ''
authors:
- Nicholas DiGiuseppe
- James A. Jones
tags:
- Debugging
- Fault behavior
- Fault localization
categories: []
date: '2015-08-01'
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
publishDate: '2023-09-22T06:26:19.193434Z'
publication_types:
- '2'
abstract: This paper presents multiple empirical experiments that investigate the
  impact of fault quantity and fault type on statistical, coverage-based fault localization
  techniques and fault-localization interference. Fault-localization interference
  is a phenomenon revealed in earlier studies of coverage-based fault localization
  that causes faults to obstruct, or interfere, with other faults’ ability to be localized.
  Previously, it had been asserted that a fault-localization technique’s effectiveness
  was negatively correlated to the quantity of faults in the program. To investigate
  these beliefs, we conducted an experiment on six programs consisting of more than
  72,000 multiple-fault versions. Our data suggests that the impact of multiple faults
  exerts a significant, but slight influence on fault-localization effectiveness.
  In addition, faults were categorized according to four existing fault-taxonomies
  and found no correlation between fault type and fault-localization interference.
  In general, even in the presence of many faults, at least one fault was found by
  fault localization with similar effectiveness. Additionally, our data exhibits that
  fault-localization interference is prevalent and exerts a meaningful influence that
  may cause a fault’s localizability to vary greatly. Because almost all real-world
  software contains multiple faults, these results affect the practical use and understanding
  of statistical fault-localization techniques.
publication: '*Empirical Software Engineering*'
doi: 10.1007/s10664-014-9304-1
links:
- name: URL
  url: https://doi.org/10.1007/s10664-014-9304-1
---
