---
# Documentation: https://wowchemy.com/docs/managing-content/

title: Dynamic invariant detection for relational databases
subtitle: ''
summary: ''
authors:
- Jake Cobb
- James A. Jones
- Gregory M. Kapfhammer
- Mary Jean Harrold
tags:
- dynamic invariants
- relational databases
- schema modification
categories: []
date: '2011-07-01'
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
publishDate: '2023-09-22T06:26:20.818271Z'
publication_types:
- '1'
abstract: Despite the many automated techniques that benefit from dynamic invariant
  detection, to date, none are able to capture and detect dynamic invariants at the
  interface of a program and its databases. This paper presents a dynamic invariant
  detection method for relational databases and for programs that use relational databases
  and an implementation of the approach that leverages the Daikon dynamic-invariant
  engine. The method defines a mapping between relational database elements and Daikon's
  notion of program points and variable observations, thus enabling row-level and
  column-level invariant detection. The paper also presents the results of two empirical
  evaluations on four fixed data sets and three subject programs. The first study
  shows that dynamically detecting and inferring invariants in a relational database
  is feasible and 55% of the invariants produced for each subject are meaningful.
  The second study reveals that all of these meaningful invariants are schema-enforceable
  using standards-compliant databases and many can be checked by databases with only
  limited schema constructs.
publication: '*Proceedings of the Ninth International Workshop on Dynamic Analysis*'
doi: 10.1145/2002951.2002955
links:
- name: URL
  url: https://doi.org/10.1145/2002951.2002955
---
