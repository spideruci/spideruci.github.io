---
# Documentation: https://wowchemy.com/docs/managing-content/

title: Generating descriptions for screenshots to assist crowdsourced testing
subtitle: ''
summary: ''
authors:
- Di Liu
- Xiaofang Zhang
- Yang Feng
- James A. Jones
tags:
- Task analysis
- Training
- Buildings
- Computer bugs
- Feature extraction
- Mobile applications
- Testing
categories: []
date: '2018-03-01'
lastmod: 2023-09-21T23:26:18-07:00
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
publishDate: '2023-09-22T06:26:18.279225Z'
publication_types:
- '1'
abstract: Crowdsourced software testing has been shown to be capable of detecting
  many bugs and simulating real usage scenarios. As such, it is popular in mobile-application
  testing. However in mobile testing, test reports often consist of only some screenshots
  and short text descriptions. Inspecting and under-standing the overwhelming number
  of mobile crowdsourced test reports becomes a time-consuming but inevitable task.
  The paucity and potential inaccuracy of textual information and the well-defined
  screenshots of activity views within mobile applications motivate us to propose
  a novel technique to assist developers in understanding crowdsourced test reports
  by automatically describing the screenshots. To reach this goal, in this paper,
  we propose a fully automatic technique to generate descriptive words for the well-defined
  screenshots. We employ the test reports written by professional testers to build
  up language models. We use the computer-vision technique, namely Spatial Pyramid
  Matching (SPM), to measure similarities and extract features from the screenshot
  images. The experimental results, based on more than 1000 test reports from 4 industrial
  crowdsourced projects, show that our proposed technique is promising for developers
  to better understand the mobile crowdsourced test reports.
publication: '*2018 IEEE 25th International Conference on Software Analysis, Evolution
  and Reengineering (SANER)*'
doi: 10.1109/SANER.2018.8330246
---
