---
# Documentation: https://wowchemy.com/docs/managing-content/

title: "(FSE 2026) Revealing Regressions: A Comparative Study of State-Capture Strategies in Validating Program Behavior"
subtitle: ''
summary: ''
authors:
- Hang Du
- Vijay Krishna Palepu
- James A. Jones
tags:
- Assertion Generation
- Mutation Testing
- Propagation Analysis
categories: []
date: '2026-06-30'
lastmod: 2026-06-30T23:26:21-07:00
featured: true
draft: false

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder.
# Focal points: Smart, Center, TopLeft, Top, TopRight, Left, Right, BottomLeft, Bottom, BottomRight.
image: 
caption: ''
focal_point: 'Bottom'
preview_only: false

# Projects (optional).
#   Associate this post with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `projects = ["internal-project"]` references `content/project/deep-learning/index.md`.
#   Otherwise, set `projects = []`.
projects: []
publishDate: '2026-06-30T06:26:21.730139Z'
publication_types:
- '1'

abstract: '*A central challenge in software testing is deciding which parts of a program’s state to check as evidence of correct behavior to reveal regressions. These checks are embodied as test oracles, typically as assertions in test cases. State observation strategies play a decisive role in shaping how effectively regressions can be revealed. Such strategies range from exhaustive memory snapshots to selective attribute checks via getter methods and nullability checks. These strategies are deeply embedded in both research and practice: academic work has explored heuristic- and serialization-based oracles, while industry has widely adopted snapshot testing. Despite their importance, the effects of different state-capture choices remain poorly understood from a scientific perspective. In this work, we present an experimental framework for systematically analyzing these design choices along the dimensions of observation scope, extraction approach, and extraction depth. Using this framework, we conduct an empirical study across twelve real-world projects, measuring how state-capture strategies influence regression-revealing capability and the richness of oracle information. Our findings reveal that human-written assertions often under-utilize available program state, achieving well below the fault-revealing potential of systematic observation strategies. Simple design choices, such as exposing unchecked intermediate return values, carefully selecting getters, and deepening state extraction, can yield measurable improvements (avg. 35.7%) in regression detection without needing to observe an overwhelmingly large amount of program-state data. Additionally, we highlight the challenges of observability, assertion desirability, and the trade-offs of capturing richer program states. Such insights show how small design choices can yield major differences in regression detection and potentially offer concrete directions for both tool builders and practitioners.
*'

publication: '*FSE 2026: Proceedings of the ACM on Software Engineering, Volume 3, Issue FSE*'
doi: https://doi.org/10.1145/3797107
---
