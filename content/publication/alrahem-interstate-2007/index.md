---
# Documentation: https://wowchemy.com/docs/managing-content/

title: 'INTERSTATE: A Stateful Protocol Fuzzer for SIP'
subtitle: ''
summary: ''
authors:
- Thoulfekar Alrahem
- Alex Chen
- Nick DiGiussepe
- J. Gee
- Shang-Pin Hsiao
- Sean Mattox
- Taejoon Park
- Albert Tam
- I. Harris
tags: []
categories: []
date: '2007-01-01'
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
publishDate: '2023-09-22T06:26:21.831352Z'
publication_types:
- '1'
abstract: We present the INTERSTATE fuzzer to detect security vulnerabilities in VOIP
  phones which implement Session Initiation Protocol (SIP). INTERSTATE generates an
  input sequence for a SIP phone which is constructed to reveal common security vulnerabilities.
  SIP is a stateful protocol so a state machine description of the SIP protocol is
  used by INTERSTATE to ensure that the entire state space is explored. The input
  sequence consists of SIP request messages as well as GUI input sequences which are
  remotely applied to the phone under test. The input sequence is generated to perform
  a random walk through the state space of the protocol. The application of GUI inputs
  is essential to ensure that all parts of the state machine can be tested. Faults
  are injected into SIP messages to trigger common vulnerabilities. INTERSTATE also
  checks the SIP response messages received from the phone under test against the
  expected responses described in the state machine. Checking response messages allows
  for the detection of security bugs whose impact is more subtle than a simple crash.
  We have used INTERSTATE to identify a previously unknown DoS vulnerability in an
  existing open source SIP phone. The vulnerability could not have been discovered
  without exploring multiple paths through the state machine, and applying GUI inputs
  during the fuzzing process.
publication: ''
links:
- name: URL
  url: https://www.semanticscholar.org/paper/INTERSTATE%3A-A-Stateful-Protocol-Fuzzer-for-SIP-Alrahem-Chen/ced3d57d6f67bc8d14bbd252b43c5d74aab5fc94
---
