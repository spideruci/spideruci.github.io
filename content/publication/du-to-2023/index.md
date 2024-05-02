---
# Documentation: https://wowchemy.com/docs/managing-content/

title: "To Kill a Mutant: An Empirical Study of Mutation Testing Kills"
subtitle: ''
summary: ''
authors:
- Hang Du
- Vijay Krishna Palepu
- James A. Jones
tags:
- Mutation Testing
- Mutant Detection
- Empirical Study
- Test Failure Classification
categories: []
date: '2023-07-01'
lastmod: 2023-09-21T23:26:21-07:00
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
publishDate: '2023-07-22T06:26:21.730139Z'
publication_types:
- '1'

abstract: '*Mutation testing has been used and studied for over four decades as a method to assess the strength of a test suite. This technique adds an artificial bug (i.e., a mutation) to a program to produce a mutant, and the test suite is run to determine if any of its test cases are sufficient to detect this mutation (i.e., kill the mutant). In this situation, a test case that fails is the one that kills the mutant. However, little is known about the nature of these kills. In this paper, we present an empirical study that investigates the nature of these kills. We seek to answer questions, such as: How are test cases failing so that they contribute to mutant kills? How many test cases fail for each killed mutant, given that only a single failure is required to kill that mutant? How do program crashes contribute to kills, and what are the origins and nature of these crashes? We found several revealing results across all subjects, including the substantial contribution of "crashes" to test failures leading to mutant kills, the existence of diverse causes for test failures even for a single mutation, and the specific types of exceptions that commonly instigate crashes. We posit that this study and its results should likely be taken into account for practitioners in their use of mutation testing and interpretation of its mutation score, and for researchers who study and leverage mutation testing in their future work.*'

publication: '*ISSTA 2023: Proceedings of the 32nd ACM SIGSOFT International Symposium on Software Testing and Analysis*'
doi: 10.1145/3597926.3598090
---
