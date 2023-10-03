---
# Documentation: https://wowchemy.com/docs/managing-content/

title: Localizing SQL faults in database applications
subtitle: ''
summary: ''
authors:
- Sarah R. Clark
- Jake Cobb
- Gregory M. Kapfhammer
- James A. Jones
- Mary Jean Harrold
tags:
- Instruments
- Java
- Marketing and sales
- Measurement
- Relational databases
- Software
categories: []
date: '2011-11-01'
lastmod: 2023-09-21T23:26:20-07:00
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
publishDate: '2023-09-22T06:26:20.311396Z'
publication_types:
- '1'
abstract: This paper presents a new fault-localization technique designed for applications
  that interact with a relational database. The technique uses dynamic information
  specific to the application's database, such as Structured Query Language (SQL)
  commands, to provide a fault-location diagnosis. By creating statement-SQL tuples
  and calculating their suspiciousness, the presented method lets the developer identify
  the database commands and the program statements likely to cause the failures. The
  technique also calculates suspiciousness for statement-attribute tuples and uses
  this information to identify SQL fragments that are statistically likely to be responsible
  for the suspiciousness of that SQL command. The paper reports the results of two
  empirical studies. The first study compares existing and database-aware fault-localization
  methods, and reveals the strengths and limitations of prior techniques, while also
  highlighting the effectiveness of the new approach. The second study demonstrates
  the benefits of using database information to improve understanding and reduce manual
  debugging effort.
publication: '*2011 26th IEEE/ACM International Conference on Automated Software Engineering
  (ASE 2011)*'
doi: 10.1109/ASE.2011.6100056
---
