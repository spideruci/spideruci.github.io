---
# Leave the homepage title empty to use the site title
title:
date: 2022-10-24
type: landing

sections:
  - block: hero
    content:
      title: |
        Spider Lab 
      image:
        filename: welcome.jpg
      text: |
        <br>
        The Spider Lab at University of California, Irvine consists of researchers committed to enabling the automation of many software engineering tasks to reduce their costs, while improving the software''s quality.
        Specifically, the Spider Lab is dedicated to improving the quality of software and the efficiency with which it is developed and maintained. The research areas of software analysis, testing, and visualization are utilized to enable software developers to fathom the complex interior workings of their software, specifically for finding and fixing software bugs.
  
  - block: collection
    content:
      title: Latest News
      subtitle:
      text:
      count: 5
      filters:
        author: ''
        category: ''
        exclude_featured: false
        publication_type: ''
        tag: ''
      offset: 0
      order: desc
      page_type: post
    design:
      view: card
      columns: '1'
  
  - block: markdown
    content:
      title:
      subtitle:
      text: |
        {{% cta cta_link="./people/" cta_text="Meet the team →" %}}
    design:
      columns: '1'
---