---
# Documentation: https://wowchemy.com/docs/managing-content/

title: Improving efficiency of dynamic analysis with dynamic dependence summaries
subtitle: ''
summary: ''
authors:
- Vijay Krishna Palepu
- Guoqing Xu
- James A. Jones
tags:
- data-flow
- dynamic analysis
- dynamic slicing
- program analysis
- summarization
categories: []
date: '2013-11-01'
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
publishDate: '2023-09-22T06:26:19.295445Z'
publication_types:
- '1'
abstract: Modern applications make heavy use of third-party libraries and components,
  which poses new challenges for efficient dynamic analysis. To perform such analyses,
  transitive dependent components at all layers of the call stack must be monitored
  and analyzed, and as such may be prohibitively expensive for systems with large
  libraries and components. As an approach to address such expenses, we record, summarize,
  and reuse dynamic dataflows between inputs and outputs of components, based on dynamic
  control and data traces. These summarized dataflows are computed at a fine-grained
  instruction level; the result of which, we call \"dynamic dependence summaries.\"
  Although static summaries have been proposed, to the best of our knowledge, this
  work presents the first technique for dynamic dependence summaries. The benefits
  to efficiency of such summarization may be afforded with losses of accuracy. As
  such, we evaluate the degree of accuracy loss and the degree of efficiency gain
  when using dynamic dependence summaries of library methods. On five large programs
  from the DaCapo benchmark (for which no existing whole-program dynamic dependence
  analyses have been shown to scale) and 21 versions of NANOXML, the summarized dependence
  analysis provided 90% accuracy and a speed-up of 100% (i.e., ×2), on average, when
  compared to traditional exhaustive dynamic dependence analysis.
publication: '*Proceedings of the 28th IEEE/ACM International Conference on Automated
  Software Engineering*'
doi: 10.1109/ASE.2013.6693066
links:
- name: URL
  url: https://doi.org/10.1109/ASE.2013.6693066
---
