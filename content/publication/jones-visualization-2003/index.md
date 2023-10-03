---
# Documentation: https://wowchemy.com/docs/managing-content/

title: Visualization for Fault Localization
subtitle: ''
summary: ''
authors:
- James A. Jones
- M. J. Harrold
- J. Stasko
tags: []
categories: []
date: '2003-01-01'
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
publishDate: '2023-09-22T06:26:22.852035Z'
publication_types:
- '1'
abstract: 'Software errors significantly impact software productivity and quality.
  Attempts to reduce the number of delivered faults are estimated to consume between
  50% and 80% of the development and maintenance effort [4]. Debugging is one of the
  most time-consuming, and thus expensive, tasks required to reduce the number of
  delivered faults in a program. Because software debugging is so expensive, researchers
  have investigated techniques and tools to assist developers with these tasks (e.g.,
  [1, 3, 7]). However, these tools often do not scale to large programs or they require
  extensive manual intervention. This lack of effective tools hinders the development
  and maintenance process. Studies show that locating the errors is the most difficult
  and time-consuming component of the debugging process (e.g., [8]). Pan and Spafford
  observed that developers consistently perform four tasks when attempting to locate
  the errors in a program: (1) identify statements involved in failures; (2) select
  suspicious statements that might contain faults; (3) hypothesize about suspicious
  faults; and (4) restore program variables to a specific state [6]. A source-code
  debugger can help with the first task: a developer runs the program, one line at
  a time, with a test case that caused it to fail, and during this execution, the
  developer can inspect the results produced by the execution of each statement in
  the program. Information about incorrect results at a statement can help a developer
  locate the source of the problem. Stepping through large programs one statement
  at a time, however, and inspecting the results of the execution can be very time
  consuming. Thus, developers often try to localize the problem area by working backwards
  from the location of the failure (e.g., computing a slice). By considering all statements
  that affect the location in which an incorrect value occurred, a developer may be
  able to locate the cause of the failure. A source-code debugger can also help a
  developer with the fourth task: a developer can set breakpoints, reset the program
  state, and execute the program with the modified state. This process may help a
  developer concentrate on smaller regions of code that may be the cause of the failure.
  Although these tools can help developers locate faults, there are several aspects
  of this fault-localization that can be improved. First, even with source-code debuggers
  and slicers, the manual process of identifying the location of the faults can be
  very time consuming. A technique that can automate, or partially automate, the process
  can provide significant savings. Second, because these tools lead developers to
  focus their attention locally instead of providing a global view of the software,
  interacting faults are difficult to detect. An approach that provides the developer
  with a global view of the software, while still giving access to the local view,
  can provide a developer with more useful information. Third, the tools use results
  of only one execution of the program instead of using information provided by many
  executions of the program; such information is typically an artifact of the testing
  process. A tool that provides information about many executions of the program lets
  the developer understand more complex relationships in the system. To address these
  problems, we have begun to develop visualization techniques and tools that can improve
  developers’ ability to locate faults. Techniques and heuristics such as those described
  above may help a developer focus on areas of the program where faults may occur.
  However, with large programs and multiple faults, the huge amount of data produced
  by such an approach, if reported in a textual form, may be difficult'
publication: ''
links:
- name: URL
  url: https://www.semanticscholar.org/paper/Visualization-for-Fault-Localization-Jones-Harrold/a512b04457cd02779508b60662fd5c632abab78d
---
