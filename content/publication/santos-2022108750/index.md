---
# Documentation: https://wowchemy.com/docs/managing-content/

title: Towards the optimal orchestration of steerable mmWave backhaul reconfiguration
subtitle: ''
summary: ''
authors:
- Ricardo Santos
- Nina Skorin-Kapov
- Hakim Ghazzai
- Andreas Kassler
- Gia Khanh Tran
tags:
- Wireless backhaul
- mmWave
- Reconfiguration
- Optimization
- MILP model
categories: []
date: '2022-01-01'
lastmod: 2023-10-09T10:22:02+02:00
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
publishDate: '2023-10-09T08:22:01.618404Z'
publication_types:
- '2'
abstract: Future generations of mobile networks will require increased backhaul capacity
  to connect a massive amount of small cells (SCs) to the network. Since having an
  optical connection to each SC might be infeasible, mmWave links are an interesting
  alternative due to their large available bandwidth. An advantage of a wireless backhaul
  is that the topology can be reconfigured to adapt to changing traffic demands, new
  operator policies, or to rapidly overcome network failures. In this work, we investigate
  the problem of orchestrating the reconfiguration of mmWave wireless backhaul networks
  with mechanically steerable antennas assuming green backhaul operation where nodes
  are turned off when not in use. The orchestration involves scheduling and coordinating
  the powering on/off of nodes, the rotation of antennas to achieve alignment for
  link establishment, and setting up and tearing down links to minimize packet loss
  during the reconfiguration. We model the problem as a Mixed Integer Linear Program
  (MILP) for optimal orchestration and propose a sub-optimal reduced MILP for larger
  instances. Numerical results for different topologies using a realistic traffic
  trace indicate that optimizing reconfiguration orchestration can significantly reduce
  packet loss in comparison to a straightforward reconfiguration approach, enabling
  a smooth transition between target mmWave backhaul topologies.
doi: https://doi.org/10.1016/j.comnet.2021.108750
publication: '*Computer Networks*, Vol. 205, PP. 108750, DOI: https://doi.org/10.1016/j.comnet.2021.108750'
links:
- name: URL
  url: https://www.sciencedirect.com/science/article/pii/S1389128621005958
---
