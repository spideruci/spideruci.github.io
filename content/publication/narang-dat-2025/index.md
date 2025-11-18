---
# Documentation: https://wowchemy.com/docs/managing-content/

title: "(ASE 2025) What's DAT Smell? Untangling and Weaving the Disjoint Assertion Tangle Test Smell"
subtitle: ''
summary: ''
authors:
- Monil Narang
- Hang Du
- James A. Jones
tags:
- Test Smell
- Test Code Refactoring
- Eager Test
categories: []
date: '2025-10-17'
lastmod: 2025-10-17T23:26:21-07:00
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
publishDate: '2025-10-17T06:26:21.730139Z'
publication_types:
- '1'

abstract: '*In this work, we characterize a novel test-code smell—Disjoint Assertion Tangle (DAT)—which occurs when a test method verifies multiple, logically unrelated behaviors that can be separated. We propose a program analysis-based approach that automatically detects DAT and refactors DAT tests into separate focused test methods. We implemented this approach as a tool called U2W. By separating unrelated testing logic, U2W enhances readability, maintainability, and fault localization, while exposing hidden test clones and duplicated code. It then seizes these opportunities by converting structurally similar tests into compact, parameterized unit tests (PUTs), reducing redundancy and enabling more scalable, extensible test designs. To evaluate our approach and tool, we conducted a number of evaluations: (1) a large-scale, quantitative study to study the prevalence of the test smell and the effects of their refactoring, (2) a user survey to assess developers’ opinions and preferences of the unrefactored and refactored test code, and (3) pull requests that were issued to original project maintainers to assess the acceptability of our refactorings. Our quantitative study was conducted on 42,334 tests across 49 open-source projects. We found the DAT smell in 95.9% of the subject projects, affecting an average of 8.59% of analyzed tests. In total, we identified and refactored 3,638 smelly tests, untangled them into 31,837 test-execution logics, and then weaved 14,343 of them into 1,713 extensible PUT methods. These refactorings reduced the executable test-code lines in smelly tests by an average of 36.33%. Our user survey involving 49 industrial and academic participants demonstrated strong preference for our refactored test cases over their original, unrefactored versions. Additionally, we submitted 19 pull requests based on our automated refactorings; 16 of these were accepted by project maintainers. These results suggest that U2W effectively improves test-suite quality, and validate our novel test smell aligns closely with developers’ intuitions and practices.

![Technique Overview](flow.png)
*Figure: Technique Overview*
*'

publication: '*ASE 2025 (To Appear): Proceedings of the IEEE/ACM XXth International Conference on Automated Software Engineering*'

doi: https://www.researchgate.net/profile/Hang-Du-13/publication/396245588_What's_DAT_Smell_Untangling_and_Weaving_the_Disjoint_Assertion_Tangle_Test_Smell/links/68e4559ed221a404b2a5cbc3/Whats-DAT-Smell-Untangling-and-Weaving-the-Disjoint-Assertion-Tangle-Test-Smell.pdf?origin=publicationDetail&_sg%5B0%5D=LJUWwrzYlF1g0GMETEmmm1hi3lxa69K1m0qfZWqrpGCab6hOV40NmondSN6qqBi5zDKq-afpstugTuk4onKqLw.9Cp3lMUE7vMx1SQI9ERob4umDE_kMS_RbQgsWoDADB1zIJIxf74roB5OTR255nzz6NTnQ6hGbBZr6_SZ3iBfqQ&_sg%5B1%5D=s3fSCCns2L6vE___tBytmOWcxpt3bbuiTJid7D35Dq_k5TO4ITgxxpfKlkUiun19O6FMznWT-Vmbv94Xp4Q2HLbdTG1MysU-iFZ7NEO0ZVzz.9Cp3lMUE7vMx1SQI9ERob4umDE_kMS_RbQgsWoDADB1zIJIxf74roB5OTR255nzz6NTnQ6hGbBZr6_SZ3iBfqQ&_iepl=&_rtd=eyJjb250ZW50SW50ZW50IjoibWFpbkl0ZW0ifQ%3D%3D&_tp=eyJjb250ZXh0Ijp7ImZpcnN0UGFnZSI6InB1YmxpY2F0aW9uIiwicGFnZSI6InB1YmxpY2F0aW9uIiwicG9zaXRpb24iOiJwYWdlSGVhZGVyIn19
---
