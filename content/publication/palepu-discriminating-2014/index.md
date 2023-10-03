---
# Documentation: https://wowchemy.com/docs/managing-content/

title: Discriminating influences among instructions in a dynamic slice
subtitle: ''
summary: ''
authors:
- Vijay Krishna Palepu
- James A. Jones
tags:
- dynamic dependence analysis
- dynamic slicing
- program analysis
- program understanding
- software analysis
categories: []
date: '2014-09-01'
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
publishDate: '2023-09-22T06:26:19.091857Z'
publication_types:
- '1'
abstract: Dynamic slicing is an analysis that operates on program execution models
  (e.g., dynamic dependence graphs) to support the interpreation of program-execution
  traces. Given an execution event of interest (i.e., the slicing criterion), it solves
  for all instruction-execution events that either affect or are affected by that
  slicing criterion, and thereby reduces the search space to find influences within
  execution traces. Unfortunately, the resulting dynamic slices are still often prohibitively
  large for many uses. Despite this reduction search space, the dynamic slices are
  often still prohibitively large for many uses, and moreover, are provided without
  guidance of which and to what degree those influences are exerted. In this work,
  we present a novel approach to quantify the relevance of each instruction-execution
  event within a dynamic slice by its degree of relative influence on the slicing
  criterion. As such, we augment the dynamic slice with dynamic-relevance measures
  for each event in the slice, which can be used to guide and prioritize inspection
  of the events in the slice. We conducted an experiment that evaluates the ability
  of existing dynamic slicing and our approach, using dynamic relevance, to correctly
  identify sources of execution influence and state propagation. The results of the
  experiment show that inspections that were guided by traditional dynamic slicing
  to find the root cause for a failure reduced the search space by, on average, 61.3%.
  Further, inspections guided with the assistance of the new dynamic relevance reduced
  the search space by 96.2%.
publication: '*Proceedings of the 29th ACM/IEEE International Conference on Automated
  Software Engineering*'
doi: 10.1145/2642937.2642962
links:
- name: URL
  url: https://doi.org/10.1145/2642937.2642962
---
