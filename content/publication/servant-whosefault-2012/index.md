---
# Documentation: https://wowchemy.com/docs/managing-content/

title: 'WhoseFault: Automatic developer-to-fault assignment through fault localization'
subtitle: ''
summary: ''
authors:
- Francisco Servant
- James A. Jones
tags:
- Correlation
- Data mining
- developer assignment
- expertise assignment
- fault localization
- History
- Informatics
- Measurement
- mining software repositories
- Software
- Software algorithms
categories: []
date: '2012-06-01'
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
publishDate: '2023-09-22T06:26:19.909776Z'
publication_types:
- '1'
abstract: 'This paper describes a new technique, which automatically selects the most
  appropriate developers for fixing the fault represented by a failing test case,
  and provides a diagnosis of where to look for the fault. This technique works by
  incorporating three key components: (1) fault localization to inform locations whose
  execution correlate with failure, (2) history mining to inform which developers
  edited each line of code and when, and (3) expertise assignment to map locations
  to developers. To our knowledge, the technique is the first to assign developers
  to execution failures, without the need for textual bug reports. We implement this
  technique in our tool, WHOSEFAULT, and describe an experiment where we utilize a
  large, open-source project to determine the frequency in which our tool suggests
  an assignment to the actual developer who fixed the fault. Our results show that
  81% of the time, WHOSEFAULT produced the same developer that actually fixed the
  fault within the top three suggestions. We also show that our technique improved
  by a difference between 4% and 40% the results of a baseline technique. Finally,
  we explore the influence of each of the three components of our technique over its
  results, and compare our expertise algorithm against an existing expertise assessment
  technique and find that our algorithm provides greater accuracy, by up to 37%.'
publication: '*2012 34th International Conference on Software Engineering (ICSE)*'
doi: 10.1109/ICSE.2012.6227208
---
