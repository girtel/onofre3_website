---
# Documentation: https://wowchemy.com/docs/managing-content/

title: 'When less is more powerful: Shapley value attributed ablation with augmented
  learning for practical time series sensor data classification'
subtitle: ''
summary: ''
authors:
- Arijit AND Marin, Leandro AND Jara, Antonio J. Ukil
tags: []
categories: []
date: '2022-11-01'
lastmod: 2023-10-09T10:21:53+02:00
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
publishDate: '2023-10-09T08:21:53.209053Z'
publication_types:
- '2'
abstract: 'Time series sensor data classification tasks often suffer from training
  data scarcity issue due to the expenses associated with the expert-intervened annotation
  efforts. For example, Electrocardiogram (ECG) data classification for cardio-vascular
  disease (CVD) detection requires expensive labeling procedures with the help of
  cardiologists. Current state-of-the-art algorithms like deep learning models have
  shown outstanding performance under the general requirement of availability of large
  set of training examples. In this paper, we propose Shapley Attributed Ablation
  with Augmented Learning: ShapAAL, which demonstrates that deep learning algorithm
  with suitably selected subset of the seen examples or ablating the unimportant ones
  from the given limited training dataset can ensure consistently better classification
  performance under augmented training. In ShapAAL, additive perturbed training augments
  the input space to compensate the scarcity in training examples using Residual Network
  (ResNet) architecture through perturbation-induced inputs, while Shapley attribution
  seeks the subset from the augmented training space for better learnability with
  the goal of better general predictive performance, thanks to the “efficiency” and
  “null player” axioms of transferable utility games upon which Shapley value game
  is formulated. In ShapAAL, the subset of training examples that contribute positively
  to a supervised learning setup is derived from the notion of coalition games using
  Shapley values associated with each of the given inputs’ contribution into the model
  prediction. ShapAAL is a novel push-pull deep architecture where the subset selection
  through Shapley value attribution pushes the model to lower dimension while augmented
  training augments the learning capability of the model over unseen data. We perform
  ablation study to provide the empirical evidence of our claim and we show that proposed
  ShapAAL method consistently outperforms the current baselines and state-of-the-art
  algorithms for time series sensor data classification tasks from publicly available
  UCR time series archive that includes different practical important problems like
  detection of CVDs from ECG data.'
doi: 10.1371/journal.pone.0277975
publication: '*PLOS ONE*, Vol. 17, No. 11, PP. 1-28, DOI: 10.1371/journal.pone.0277975'
links:
- name: URL
  url: https://doi.org/10.1371/journal.pone.0277975
---
