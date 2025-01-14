---
# Documentation: https://wowchemy.com/docs/managing-content/
title: "ICSE & MSR 2025"
subtitle: ""
summary: Our lab is excited to announce that we have two papers accepted for presentation at ICSE and MSR this year in Ottawa, Canada! Congratulations to Hang Du and Yi-Hung Chou on this achievement. We look forward to connecting with everyone there!
authors: []
tags: []
categories: blog
date: 2025-01-14 06:27:01
lastmod: 2025-01-14 06:27:01

featured: true
draft: false

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder.
# Focal points: Smart, Center, TopLeft, Top, TopRight, Left, Right, BottomLeft, Bottom, BottomRight.
image:
  caption: ""
  focal_point: ""
  preview_only: false

# Projects (optional).
#   Associate this post with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `projects = ["internal-project"]` references `content/project/deep-learning/index.md`.
#   Otherwise, set `projects = []`.
projects: []
---

Hang Du, Vijay Krishna Palepu, James A. Jones, "Leveraging Propagated Infection to Crossfire Mutants"

Abstract: Mutation testing was proposed to identify weaknesses in test suites by repeatedly generating artificially faulty versions of the software (i.e., *mutants*) and determining if the test suite is sufficient to detect them (i.e., *kill* them). When the tests are insufficient, each surviving mutant provides an opportunity to improve the test suite. We conducted a study and found that many such surviving mutants (up to 84% for the subjects of our study) are detectable by simply augmenting existing tests with additional assertions, or *assertion amplification*. Moreover, we find that many of these mutants are detectable by multiple existing tests, giving developers options for how to detect them. To help with these challenges, we created a technique that performs memory-state analysis to identify candidate assertions that developers can use to detect the surviving mutants. Additionally, we build upon prior research that identifies "crossfiring" opportunities -- tests that coincidentally kill multiple mutants. To this end, we developed a theoretical model that describes the varying granularities that crossfiring can occur in the existing test suite, which provide opportunities and options for how to kill surviving mutants. We operationalize this model to an accompanying technique that optimizes the assertion amplification of the existing tests to crossfire multiple mutants with fewer added assertions, optionally concentrated within fewer tests. Our experiments show that we can kill *all* surviving mutants that are detectable with existing test data with only 1.1% of the identified assertion candidates, and increasing by a factor of 6x, on average, the number of killed mutants from amplified tests, over tests that do not crossfire.


Yi-Hung Chou, Yiyang Min, April Yi Wang, James A. Jones, "Learning from Mistakes: Understanding Ad-hoc Logs through Analyzing Accidental Commits"

Abstract: Developers often insert temporary "print" or "log" instructions into their code to help them better understand runtime behavior, usually when the code is not behaving as they expected. Despite the fact that such monitoring instructions, or "ad-hoc logs," are so commonly used by developers, there is almost no existing literature that studies developers' practices in how they use them. This paucity of knowledge of the use of these ephemeral logs may be largely due to the fact that they typically only exist in the developers' local environments and are removed before they commit their code to their revision control system. In this work, we overcome this challenge by observing that developers occasionally mistakenly forget to remove such instructions before committing, and then they remove them shortly later. Additionally, we further study such developer logging practices by watching and analyzing live-streamed coding videos. Through these empirical approaches, we study where, how, and why developers use ad-hoc logs to better understand their code and its execution.We collect 27 GB of accidental commits that removed 548,880 ad-hoc logs in JavaScript from GitHub Archive repositories to provide the first large-scale dataset and empirical studies on ad-hoc logging practices. Our results reveal several illuminating findings, including a particular propensity for developers to use ad-hoc logs in asynchronous and callback functions.Our findings provide both empirical evidence and a valuable dataset for researchers and tool developers seeking to enhance ad-hoc logging practices, and potentially deepen our understanding of developers’ practices towards understanding of software’s runtime behaviors.