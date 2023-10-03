---
# Documentation: https://wowchemy.com/docs/managing-content/

title: 'CASI: preventing indirect conflicts through a live visualization'
subtitle: ''
summary: ''
authors:
- Francisco Servant
- James A. Jones
- André van der Hoek
tags:
- conflicts
- parallel work
- software configuration management
- software visualization
- workspace awareness
categories: []
date: '2010-05-01'
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
publishDate: '2023-09-22T06:26:21.123171Z'
publication_types:
- '1'
abstract: Software development is a collaborative activity that may lead to conflicts
  when changes are performed in parallel by several developers. Direct conflicts arise
  when multiple developers make changes in the same source code entity, and indirect
  conflicts are produced when multiple developers make changes to source code entities
  that depend on each other. Previous approaches of code analysis either cannot predict
  all kinds of indirect conflicts, since they can be caused by syntactic or semantic
  changes, or they produce so much information as to make them virtually useless.
  Workspace awareness techniques have been proposed to enhance software configuration
  management systems by providing developers with information about the activity that
  is being performed by other developers. Most workspace awareness tools detect direct
  conflicts while only some of them warn about potential indirect conflicts. We propose
  a new approach to the problem of indirect conflicts. Our tool CASI informs developers
  of the changes that are taking place in a software project and the source code entities
  influenced by them. We visualize this influence together with directionality and
  severity information to help developers decide whether a concrete situation represents
  an indirect conflict. We introduce our approach, explain its implementation, discuss
  its behavior on an example, and lay out several steps that we will be taking to
  improve it in the future.
publication: '*Proceedings of the 2010 ICSE Workshop on Cooperative and Human Aspects
  of Software Engineering*'
doi: 10.1145/1833310.1833317
links:
- name: URL
  url: https://doi.org/10.1145/1833310.1833317
---
