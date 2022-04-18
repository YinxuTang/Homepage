---
abstract: In software-defined networking (SDN) systems, it is a common practice to adopt a multi-controller design and control devolution techniques to improve the performance of the control plane. However, in such systems the decision making for joint switch-controller association and control devolution often involves various uncertainties, e.g., the temporal variations of controller accessibility, and computation and communication costs of switches. In practice, statistics of such uncertainties are unattainable and need to be learned in an online fashion, calling for an integrated design of learning and control. In this paper, we formulate a stochastic network optimization problem that aims to minimize time-average system costs and ensure queue stability. By transforming the problem into a combinatorial multi-armed bandit problem with long-term stability constraints, we adopt bandit learning methods and optimal control techniques to handle the exploration-exploitation tradeoff and long-term stability constraints, respectively. Through an integrated design of online learning and online control, we propose an effective Learning-Aided Switch-Controller Association and Control Devolution (LASAC) scheme. Our theoretical analysis and simulation results show that LASAC achieves a tunable tradeoff between queue stability and system cost reduction with a sublinear regret bound over a finite time horizon.
slides: ""
url_pdf: https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=9212913
publication_types:
  - "1"
authors:
  - Xi Huang
  - admin
  - Ziyu Shao
  - Yang Yang
  - Hong Xu
author_notes: []
publication: In *IEEE/ACM International Symposium on Quality of Service*
summary: ""
url_dataset: ""
url_project: ""
publication_short: In *Proceedings of IWQoS*
url_source: ""
url_video: ""
title: Joint Switch-Controller Association and Control Devolution for SDN Systems: An Integration of Online Control and Online Learning
doi: 10.1109/IWQoS49365.2020.9212913
featured: true
tags: []
projects: []
image:
  caption: ""
  focal_point: ""
  preview_only: false
date: 2022-04-18T12:40:52.410Z
url_slides: ""
publishDate: 2017-01-01T00:00:00.000Z
url_poster: ""
url_code: ""
---
