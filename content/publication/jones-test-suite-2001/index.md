---
# Documentation: https://wowchemy.com/docs/managing-content/

title: Test-suite reduction and prioritization for modified condition/decision coverage
subtitle: ''
summary: ''
authors:
- J.A. Jones
- M.J. Harrold
tags:
- Costs
- Educational institutions
- Electronic switching systems
- FAA
- Performance evaluation
- Safety
- Software algorithms
- Software maintenance
- Software testing
- System testing
categories: []
date: '2001-11-01'
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
publishDate: '2023-09-22T06:26:22.446253Z'
publication_types:
- '1'
abstract: Software testing is particularly expensive for developers of high-assurance
  software, such as software that is produced for commercial airborne systems. One
  reason for this expense is the Federal Aviation Administration's requirement that
  test suites be modified condition/decision coverage (MC/DC) adequate. Despite its
  cost, there is evidence that MC/DC is an effective verification technique, and can
  help to uncover safety faults. As the software is modified and new test cases are
  added to the test suite, the test suite grows, and the cost of regression testing
  increases. To address the test-suite size problem, researchers have investigated
  the use of test-suite reduction algorithms, which identify a reduced test suite
  that provides the same coverage of the software, according to some criterion, as
  the original test suite, and test-suite prioritization algorithms, which identify
  an ordering of the test cases in the test suite according to some criteria or goals.
  Existing test-suite reduction and prioritization techniques, however, may not be
  effective in reducing or prioritizing MC/DC-adequate test suites because they do
  not consider the complexity of the criterion. The paper presents new algorithms
  for test-suite reduction and prioritization that can be tailored effectively for
  use with MC/DC. The paper also presents the results of a case study of the test-suite
  reduction algorithm.
publication: '*Proceedings IEEE International Conference on Software Maintenance.
  ICSM 2001*'
doi: 10.1109/ICSM.2001.972715
---
