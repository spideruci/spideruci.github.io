---
# Documentation: https://wowchemy.com/docs/managing-content/

title: "(ISSTA 2026) How Does Killing Surviving Mutants Help Detect Real Bugs with Assertion Generation? A Controlled Experiment"
subtitle: ''
summary: ''
authors:
- Hang Du
- Vijay Krishna Palepu
- James A. Jones
tags:
- Mutation Testing
- Assertion Generation
- Coupling Effect
- Bug Detection
categories: []
date: '2026-09-27T00:00:00Z'
lastmod: 2026-09-27T00:00:00-07:00
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
publishDate: '2026-09-27T00:00:00Z'
publication_types:
- '1'

abstract: '*Killing surviving mutants is a central activity of mutation testing. This activity is motivated by the coupling-effect hypothesis: tests that expose simple artificial faults can also detect more complex, previously unseen real bugs. Despite these claimed benefits, automated studies have not directly measured the causal impact of mutant killing on real-bug detection. This limitation stems from open-ended mutant-killing strategies and a fundamental evaluation asymmetry that obscures causal attribution. In this work, we present the first large-scale controlled experiment that directly measures whether killing surviving mutants, without knowledge of future real bugs, would have enabled their detection. We model mutant killing as a selective, incremental process under realistic budget constraints, and we restrict test improvements to assertion augmentation, thereby targeting the subset of surviving mutants whose survival stems from revealability gaps in existing tests. This restriction enables precise attribution of each test augmentation to a specific mutant-killing action. To support the experiment, we design a fully automated, fault-based assertion-augmentation technique that operates uniformly on mutants and real bugs and integrate it into Defects4J. Our controlled experiment yields several key empirical insights: (1) Across 642 Defects4J bugs, we find that 104 bugs would become detectable by adding an additional assertion to an existing passing, non-triggering test. (2) When coupling exists, a real bug is, on average, coupled with 21 surviving mutants, through which mutant killing can produce triggering tests. This number is substantially higher than the average of two mutants reported in prior studies. In those studies, coupling is inferred solely from documented bug-fixing tests rather than from tests derived via mutant killing. (3) Among these bugs, 63 of the 104 are detectable through a principled mutant-killing (test augmentation) process. Notably, killing a randomly selected 30% of relevant surviving mutants, using only one assertion per mutant, suffices to detect 84.5% of these bugs. (4) By substituting mutants with real bugs and comparing their resulting assertion augmentation outputs, we find that real bugs induce broader behavioral effects than mutants, affecting more memory state locations, variables, and tests. (5) When mutation-derived assertions detect real bugs, they validate program outputs that overlap with, and are often strict subsets of, those affected by the real bugs. This offers a mechanistic explanation for why killing simple mutants can enable the detection of more complex real bugs.
*'

publication: '*ISSTA 2026: Proceedings of the ACM on Software Engineering, Volume 3, Issue ISSTA*'
doi: 10.1145/3832232
---
