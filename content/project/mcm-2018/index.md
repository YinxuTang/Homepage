---
title: " MCM 2018: Energy Production"
subtitle: "Plan of A New Energy Compact by Energy Profiles: Arizona, California,
  New Mexico, and Texas"
date: 2018-02-13T13:46:59.518Z
summary: >-
  * Perform data analysis and modeling to determine the "best" energy profile and to
  predict the energy profile in the future

    * Utilize ***Entropy Weight Method (EWM)*** to assess the energy profile and determine the best energy profile
    * Apply two ***Time Series Forecasting Analysis (TSFA)*** methods to predict the energy profile

      * ***Gray Model: GM (1,1)***
      * ***Back Propagation Neural Network*** with 10 hidden layers
  * Transform the compact goals to the optimization targets

    * Adopt ***Multivariate Linear Regression*** to solve the optimization problem
draft: false
featured: false
authors:
  - admin
  - Guanzhou Hu
  - Xinyu Zhang
tags:
  - Competition
links:
  - url: https://drive.google.com/file/d/1jE0P-w7LH-GboTBmVe_zY2K0PuoHQGeQ/view?usp=sharing
    name: PDF
image:
  filename: featured.jpg
  focal_point: Smart
  preview_only: false
  caption: Relationship Between the Energy Variables
  alt_text: ""
---
## **Summary**

A new energy compact of Arizona, California, New Mexico, and Texas is coming into being, devoted to improving clean energy usage.

With data from State Energy Data System, a static structure of energy usage in each state is constructed. This consists of pie charts showing energy consumption ratio of each source, and a column chart to compare energy consumed by the end-use sectors and the electric power sector. Four abstract indicators: energy consumption per capita, clean energy usage ratio, total consumption of all petroleum products, and the ratio of clean electricity generated, are then extracted from the structural variables, and together they constitute the energy profile.

By plotting the evolution of elements in energy profile over time, time series of all four indicators are derived. In addition, two more indicators: change rate of clean energy ratio and that of energy consumption per capita, are acquired. Indicators are then used to assess the energy profile. Weights of indicators are generated through *matrix-modified entropy method*. The weighted average of the scores for six indicators stands for the superiority in clean energy usage, and Arizona has the ”best“ energy profile by this criteria.

It turned out that energy consumption from clean energy matters most in the assessment of energy profile, so we focused on it in the following steps. By two approaches, *gray model* and *BP neural network*, predictions on the energy consumption from each clean energy source in each state are made respectively. Results show that the total clean energy consumption reaches $2.19$ and $2.45$ Million Billion Btu up to 2025 and 2050 respectively, and all four states' clean energy usage proportion level off to 10%.

To set the target of clean energy usage in 2025 and 2050, we first come up with an evaluation index defined as $I=\alpha\cdot\left(\sum_{i=1}^4 \sum_{j=1}^6 \eta_{ij} \sigma_{ij}\right)$, where $\alpha$ is the *flare factor*; $\eta_{ij}$ is *utilization efficiency*; and $\sigma_{ij}$ is the consumption quantity of the $j$th energy by the $i$th state bounded in a certain range. To optimize the index, we can either promote development of effeciency $\eta_{ij}$, or obtain the best $\sigma_{ij}$ distribution through linear programming. 

According to the approaches above, suggestions such as establishment of platforms for technology communication, and an energy deployment system are made to help the compact reach the optimum.



## **Key Words**

clean energy; entropy method; time series forecast; linear programming
