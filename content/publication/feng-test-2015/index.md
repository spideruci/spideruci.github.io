---
# Documentation: https://wowchemy.com/docs/managing-content/

title: Test report prioritization to assist crowdsourced testing
subtitle: ''
summary: ''
authors:
- Yang Feng
- Zhenyu Chen
- James A. Jones
- Chunrong Fang
- Baowen Xu
tags:
- Crowdsourcing testing
- natural language processing
- test diversity
- test report prioritization
categories: []
date: '2015-08-01'
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
publishDate: '2023-09-22T06:26:18.989928Z'
publication_types:
- '1'
abstract: 'In crowdsourced testing, users can be incentivized to perform testing tasks
  and report their results, and because crowdsourced workers are often paid per task,
  there is a financial incentive to complete tasks quickly rather than well. These
  reports of the crowdsourced testing tasks are called \"test reports\" and are composed
  of simple natural language and screenshots. Back at the software-development organization,
  developers must manually inspect the test reports to judge their value for revealing
  faults. Due to the nature of crowdsourced work, the number of test reports are often
  difficult to comprehensively inspect and process. In order to help with this daunting
  task, we created the first technique of its kind, to the best of our knowledge,
  to prioritize test reports for manual inspection. Our technique utilizes two key
  strategies: (1) a diversity strategy to help developers inspect a wide variety of
  test reports and to avoid duplicates and wasted effort on falsely classified faulty
  behavior, and (2) a risk strategy to help developers identify test reports that
  may be more likely to be fault-revealing based on past observations. Together, these
  strategies form our DivRisk strategy to prioritize test reports in crowd- sourced
  testing. Three industrial projects have been used to evaluate the effectiveness
  of test report prioritization methods. The results of the empirical study show that:
  (1) DivRisk can significantly outperform random prioritization; (2) DivRisk can
  approximate the best theoretical result for a real-world industrial mobile application.
  In addition, we provide some practical guidelines of test report prioritization
  for crowdsourced testing based on the empirical study and our experiences.'
publication: '*Proceedings of the 2015 10th Joint Meeting on Foundations of Software
  Engineering*'
doi: 10.1145/2786805.2786862
links:
- name: URL
  url: https://doi.org/10.1145/2786805.2786862
---
