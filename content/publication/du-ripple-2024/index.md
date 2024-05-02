---
# Documentation: https://wowchemy.com/docs/managing-content/

title: "Ripples of a Mutation---An Empirical Study of Propagation Effects in Mutation Testing"
subtitle: ''
summary: ''
authors:
- Hang Du
- Vijay Krishna Palepu
- James A. Jones
tags:
- Software Fault Infection
- Error Propagation
- Mutation Testing
- Dynamic Analysis
- Empirical Study
- RIPR model
categories: []
date: '2024-04-01'
lastmod: 2024-04-21T23:26:21-07:00
featured: false
draft: false

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder.
# Focal points: Smart, Center, TopLeft, Top, TopRight, Left, Right, BottomLeft, Bottom, BottomRight.
image: 
caption: "
focal_point: "
preview_only: false

# Projects (optional).
#   Associate this post with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `projects = ["internal-project"]` references `content/project/deep-learning/index.md`.
#   Otherwise, set `projects = []`.
projects: []
publishDate: '2024-04-22T06:26:21.730139Z'
publication_types:
- '1'

abstract: '*The mechanics of how a fault reveals itself as a test failure is of keen interest to software researchers and practitioners alike. An improved understanding of how faults translate to failures can guide improvements in broad facets of software testing, ranging from test suite design to automated program repair, which are premised on the understanding that the presence of faults would alter some test executions.======================================
In this work, we study such effects by mutations, as applicable in mutation testing. Mutation testing enables the generation of a large corpus of faults; thereby harvesting a large pool of mutated test runs for analysis. Specifically, we analyze more than 1.1 million mutated test runs to study if and how the underlying mutations induce infections that propagate their way to observable failures.We adopt a broad-spectrum approach to analyze such a large pool of mutated runs. For every mutated test run, we are able to determine: (a) if the mutation induced a state infection; (b) if the infection propagated through the end of the test run; and (c) if the test failed in the presence of a propagated infection.===================================================
By examining such infection-, propagation- and revealability-effects for more than 43,000 mutations executed across 1.1 million test runs we are able to arrive at some surprising findings. Our results find that once state infection is observed, propagation is frequently detected; however, a propagated infection does not always reveal itself as a test failure. We also find that a significant portion of survived mutants in our study could have been killed by observing propagated state infections that were left undetected. Finally, we also find that different mutation operators can demonstrate substantial differences in their specific impacts on the execution-to-failure ripples of the resulting mutations.*'

publication: '*ICSE 2024: Proceedings of the IEEE/ACM 46th International Conference on Software Engineering*'
doi: 10.1145/3597503.3639179
---
