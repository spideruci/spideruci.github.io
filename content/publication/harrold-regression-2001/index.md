---
# Documentation: https://wowchemy.com/docs/managing-content/

title: Regression test selection for Java software
subtitle: ''
summary: ''
authors:
- Mary Jean Harrold
- James A. Jones
- Tongyu Li
- Donglin Liang
- Alessandro Orso
- Maikel Pennings
- Saurabh Sinha
- S. Alexander Spoon
- Ashish Gujarathi
tags: []
categories: []
date: '2001-10-01'
lastmod: 2023-09-21T23:26:22-07:00
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
publishDate: '2023-09-22T06:26:22.750813Z'
publication_types:
- '1'
abstract: Regression testing is applied to modified software to provide confidence
  that the changed parts behave as intended and that the unchanged parts have not
  been adversely affected by the modifications. To reduce the cost of regression testing,
  test cases are selected from the test suite that was used to test the original version
  of the software---this process is called regression test selection. A safe regression-test-selection
  algorithm selects every test case in the test suite that may reveal a fault in the
  modified software. Safe regression-test-selection technique that, based on the use
  of a suitable representation, handles the features of the Java language. Unlike
  other safe regression test selection techniques, the presented technique also handles
  incomplete programs. The technique can thus be safely applied in the (very common)
  case of Java software that uses external libraries of components; the analysis of
  the external code is note required for the technique to select test cases for such
  software. The paper also describes RETEST, a regression-test-selection algorithm
  can be effective in reducing the size of the test suite.
publication: '*Proceedings of the 16th ACM SIGPLAN conference on Object-oriented programming,
  systems, languages, and applications*'
doi: 10.1145/504282.504305
links:
- name: URL
  url: https://doi.org/10.1145/504282.504305
---
