---
# Documentation: https://wowchemy.com/docs/managing-content/

title: Scheduling aerial resource operations for the extinction of large-scale wildfires
subtitle: ''
summary: ''
authors:
- Nina Skorin-Kapov
- Luka Mesarić
- Fernando Pereñíguez García
- Lea Skorin-Kapov
tags:
- Aerial firefighting
- Scheduling
- Mixed integer linear programming model
- Randomized greedy heuristic
- Simulated annealing
categories: []
date: '2024-01-01'
lastmod: 2023-10-09T10:21:50+02:00
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
publishDate: '2023-10-09T08:21:49.928883Z'
publication_types:
- '2'
abstract: The significant increase in large-scale wildfire events in recent decades,
  caused primarily by climate change, has resulted in a growing number of aerial resources
  being used in suppression efforts. Present-day management lacks efficient and scalable
  algorithms for complex aerial resource allocation and scheduling for the extinction
  of such fires, which is crucial to ensuring safety while maximizing the efficiency
  of operations. In this work, we present a Mixed Integer Linear Programming (MILP)
  optimization model tailored to large-scale wildfires for the daily scheduling of
  aerial operations. The main objective is to achieve a prioritized target water flow
  over all areas of operation and all time periods. Minimal target completion across
  individual areas and time periods and total water output are also maximized as secondary
  and ternary objectives, respectively. An efficient and scalable multi-start heuristic,
  combining a randomized greedy approach with simulated annealing employing large
  neighborhood search techniques, is proposed for larger instances. A diverse set
  of problem instances is generated with varying sizes and extinction strategies to
  test the approaches. Results indicate that the heuristic can achieve (near)-optimal
  solutions for smaller instances solvable by the MILP, and gives solutions approaching
  target water flows for larger problem sizes. The algorithm is parallelizable and
  has been shown to give promising results in a small number of iterations, making
  it applicable for both night-before planning and, more time-sensitive, early-morning
  scheduling.
doi: https://doi.org/10.1016/j.omega.2023.102941
publication: '*Omega*, Vol. 122, PP. 102941, DOI: https://doi.org/10.1016/j.omega.2023.102941'
links:
- name: URL
  url: https://www.sciencedirect.com/science/article/pii/S0305048323001056
---
