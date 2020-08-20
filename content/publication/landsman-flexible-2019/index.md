---
# Documentation: https://sourcethemes.com/academic/docs/managing-content/

title: A flexible integer linear programming formulation for scheduling clinician
  on-call service in hospitals
subtitle: ''
summary: ''
authors:
- David Landsman
- Huiting Ma
- Jesse Knight
- Kevin Gough
- Sharmistha Mishra
tags: []
categories: []
date: '2019-01-01'
lastmod: 2020-08-20T19:05:25-04:00
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
publishDate: '2020-08-20T23:05:24.937965Z'
publication_types:
- 3
abstract: Scheduling of personnel in a hospital environment is vital to improving
  the service provided to patients and balancing the workload assigned to clinicians.
  Many approaches have been tried and successfully applied to generate efficient schedules
  in such settings. However, due to the computational complexity of the scheduling
  problem in general, most approaches resort to heuristics to find a non-optimal solution
  in a reasonable amount of time. We designed an integer linear programming formulation
  to find an optimal schedule in a clinical division of a hospital. Our formulation
  mitigates issues related to computational complexity by minimizing the set of constraints,
  yet retains sufficient flexibility so that it can be adapted to a variety of clinical
  divisions. We then conducted a case study for our approach using data from the Infectious
  Diseases division at St. Michael's Hospital in Toronto, Canada. We analyzed and
  compared the results of our approach to manually-created schedules at the hospital,
  and found improved adherence to departmental constraints and clinician preferences.
  We used simulated data to examine the sensitivity of the runtime of our linear program
  for various parameters and observed reassuring results, signifying the practicality
  and generalizability of our approach in different real-world scenarios.
publication: '*arXiv:1910.08526*'
url_pdf: http://arxiv.org/abs/1910.08526
---
