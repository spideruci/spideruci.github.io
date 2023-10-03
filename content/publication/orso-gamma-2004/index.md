---
# Documentation: https://wowchemy.com/docs/managing-content/

title: 'GAMMA℡LA: visualization of program-execution data for deployed software'
subtitle: ''
summary: ''
authors:
- A. Orso
- J.A. Jones
- M.J. Harrold
- J. Stasko
tags:
- Data analysis
- Data visualization
- Educational institutions
- Instruments
- Monitoring
- Optimization
- Performance analysis
- Quality assurance
- Software safety
- Testing
categories: []
date: '2004-05-01'
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
publishDate: '2023-09-22T06:26:22.134446Z'
publication_types:
- '1'
abstract: "To investigate the program-execution data efficiently, we must be able\
  \ to view the data at different levels of detail. In our visualization approach,\
  \ we represent software systems at three different levels: statement level, file\
  \ level, and system level. At the statement level, we represent the actual code.\
  \ The representation at the file level provides a miniaturized view of the source\
  \ code similar to the one used in the SeeSoft system (Eick et al., 1992). The system\
  \ level uses treemaps (Shneiderman, 1992 and Bruls et al., 2000) to represent the\
  \ software and is the most abstracted level in our visualization. At each level,\
  \ coloring is used to represent one- or two-dimensional information about the code,\
  \ using the colors' hue and brightness components. The coloring technique that we\
  \ apply is a generalization of the coloring technique defined for fault-localization\
  \ by Jones and colleagues (2001). GAMMA℡LA is a toolset that implements our visualization\
  \ approach and provides capabilities for instrumenting the code, collecting program-execution\
  \ data from the field, and storing and retrieving the data locally. GAMMA℡LA is\
  \ written in Java, supports the monitoring of Java programs, and consists of three\
  \ main components: an instrumentation, execution, and coverage tool, a data collection\
  \ daemon, and a program visualizer."
publication: '*Proceedings. 26th International Conference on Software Engineering*'
doi: 10.1109/ICSE.2004.1317495
---
