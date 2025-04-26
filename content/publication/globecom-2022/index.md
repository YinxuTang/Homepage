---
title: "Social-Aware Edge Intelligence: A Constrained Graphical Bandit Approach"
publication_types:
  - "1"
authors:
  - Simeng Bian
  - Shangshang Wang
  - admin
  - Ziyu Shao
publication: In *IEEE Conference on Global Communications*
publication_short: In *Proceedings of GLOBECOM*
url_pdf: https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=10000778
doi: 10.1109/GLOBECOM48099.2022.10000778
abstract: The flourished edge intelligence has motivated the execution of machine learning tasks at the network edge. In this paper, we focus on distributing training, one of the core tasks, that is carried out by an edge server of limited communication capacity and multiple end devices. In distributed training, the key issue for the edge server is how to dynamically select a proper subset of end devices to periodically participate in the training. Such a dynamic end device selection problem is hindered by concerns like 1) unknown system dynamics, e.g., transmission latencies; 2) limited energy resources on end devices; and 3) unbalanced and non-IID data distribution over end devices. Therefore, the core challenge lies in the coordination of online learning and online control to fulfill both efficient learning of unknown statistics and guarantees of within-budget energy consumption and fairness selection. To address the above challenge, we first characterize the social ties among users of end devices as a social graph and then formulate the dynamic end device selection problem from the perspective of constrained graphical bandits. Under the formulation, we propose GRIND to effectively integrate graphical bandit learning methods with Lyapunov-drift techniques. The theoretical superiority of GRIND is not only 1) the achieved sub-linear round-averaged regret with satisfied long-term constraints but also 2) the characterization of graph structure with the independence number. Extensive simulations also verify the effectiveness of GRIND in terms of both latency reduction and long-term constraint satisfaction.
draft: false
featured: false
image:
  filename: ""
  focal_point: ""
  preview_only: false
date: 2023-04-18T14:36:06.308Z
---
