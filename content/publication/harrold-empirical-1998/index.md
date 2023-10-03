---
# Documentation: https://wowchemy.com/docs/managing-content/

title: Empirical Studies of Control Dependence Graph Size forC Programs
subtitle: ''
summary: ''
authors:
- Mary Jean Harrold
- James A. Jones
- Gregg Rothermel
tags:
- control dependence
- program analysis
- software engineering
- static analysis
categories: []
date: '1998-08-01'
lastmod: 2023-09-21T23:26:23-07:00
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
publishDate: '2023-09-22T06:26:22.956021Z'
publication_types:
- '2'
abstract: Many tools and techniques for performing software engineering tasks require
  control-dependence information, represented in the form of control-dependence graphs.
  Worst-case analysis of these graphs has shown that their size may be quadratic in
  the number of statements in the procedure that they represent. Despite this result,
  two empirical studies suggest that in practice, the relationship between control-dependence
  graph size and program size is linear. These studies, however, were performed on
  a relatively small number of Fortran procedures, all of which were derived from
  numerical methods programs. To further investigate control-dependence size, we implemented
  tools for constructing the two most popular types of control-dependence graphs,
  and ran our tools on over 3000 C functions extracted from a wide range of source
  programs. Our results support the earlier conclusions about control-dependence graph
  size.
publication: '*Empirical Software Engineering*'
doi: 10.1023/A:1008088300124
links:
- name: URL
  url: https://doi.org/10.1023/A:1008088300124
---
