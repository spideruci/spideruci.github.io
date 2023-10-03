---
# Documentation: https://wowchemy.com/docs/managing-content/

title: 'Software Behavior and Failure Clustering: An Empirical Study of Fault Causality'
subtitle: ''
summary: ''
authors:
- Nicholas DiGiuseppe
- James A. Jones
tags:
- Clustering algorithms
- Complexity theory
- Debugging
- Execution Clustering
- Failure Proximity
- Fault Understanding
- Informatics
- Measurement
- Semantics
- Software
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
publishDate: '2023-09-22T06:26:20.110033Z'
publication_types:
- '1'
abstract: To cluster executions that exhibit faulty behavior by the faults that cause
  them, researchers have proposed using internal execution events, such as statement
  profiles, to (1) measure execution similarities, (2) categorize executions based
  on those similarity results, and (3) suggest the resulting categories as sets of
  executions exhibiting uniform fault behavior. However, due to a paucity of evidence
  correlating profiles and output behavior, researchers employ multiple simplifying
  assumptions in order to justify such approaches. In this paper we present an empirical
  study of profile correlation with output behavior, and we reexamine the suitability
  of such simplifying assumptions. We examine over 4 billion test-case outputs and
  execution profiles from multiple programs with over 9000 versions. Our data provides
  evidence that with current techniques many executions should be omitted from the
  clustering analysis to provide clusters that each represent a single fault. In addition,
  our data reveals the previously undocumented effects of multiple faults on failures,
  which has implications for techniques' ability (and inability) to properly cluster.
  Our results suggest directions for the improvement of future failure-clustering
  techniques that better account for software-fault behavior.
publication: '*Verification and Validation 2012 IEEE Fifth International Conference
  on Software Testing*'
doi: 10.1109/ICST.2012.99
---
