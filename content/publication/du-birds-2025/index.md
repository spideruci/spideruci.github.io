---
# Documentation: https://wowchemy.com/docs/managing-content/

title: "(ICSE 2025) Leveraging Propagated Infection to Crossfire Mutants"
subtitle: ''
summary: ''
authors:
- Hang Du
- Vijay Krishna Palepu
- James A. Jones
tags:
- Mutation Testing
- Assertion Amplification
- Crossfiring Model
- Propagation Analysis
categories: []
date: '2024-11-15'
lastmod: 2024-11-15T23:26:21-07:00
featured: true
draft: false

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder.
# Focal points: Smart, Center, TopLeft, Top, TopRight, Left, Right, BottomLeft, Bottom, BottomRight.
image: 
caption: 'Test-level (Up) and Assertion-level (Down) Crossfiring Capabilities'
focal_point: 'Bottom'
preview_only: false

# Projects (optional).
#   Associate this post with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `projects = ["internal-project"]` references `content/project/deep-learning/index.md`.
#   Otherwise, set `projects = []`.
projects: []
publishDate: '2024-04-29T06:26:21.730139Z'
publication_types:
- '1'

abstract: '*Mutation testing was proposed to identify weaknesses in test suites by repeatedly generating artificially faulty versions of the software (i.e., mutants) and determining if the test suite is sufficient to detect them (i.e., kill them). When the tests are insufficient, each surviving mutant provides an opportunity to improve the test suite. We conducted a study and found that many such surviving mutants (up to 84% for the subjects of our study) are detectable by simply augmenting existing tests with additional assertions, or assertion amplification. Moreover, we find that many of these mutants are detectable by multiple existing tests, giving developers options for how to detect them. To help with these challenges, we created a technique that performs memory-state analysis to identify candidate assertions that developers can use to detect the surviving mutants. Additionally, we build upon prior research that identifies “crossfiring” opportunities — tests that coincidentally kill multiple mutants. To this end, we developed a theoretical model that describes the varying granularities that crossfiring can occur in the existing test suite, which provide opportunities and options for how to kill surviving mutants. We operationalize this model to an accompanying technique that optimizes the assertion amplification of the existing tests to crossfire multiple mutants with fewer added assertions, optionally concentrated within fewer tests. Our experiments show that we can kill all surviving mutants that are detectable with existing test data with only 1.1% of the identified assertion candidates, and increasing by a factor of 6x, on average, the number of killed mutants from amplified tests, over tests that do not crossfire.

![Test-level (Up) and Assertion-level (Down) Crossfiring Capabilities](heatmap.png)
*Figure: Test-level (Up) and Assertion-level (Down) Crossfiring Capabilities*
*'

publication: '*ICSE 2025 (To Appear): Proceedings of the IEEE/ACM 47th International Conference on Software Engineering*'
doi: https://doi.ieeecomputersociety.org/10.1109/ICSE55347.2025.00150
---
