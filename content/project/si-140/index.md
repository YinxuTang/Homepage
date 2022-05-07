---
title: Reverse Engineering Algorithmic Mechanism Behind WeChat Red Envelope
subtitle: ""
date: 2018-01-20T09:43:04.060Z
summary: >-
  * Conduct a large number of experiments to explore the relationship between
  the time of opening the red envelope and the amount of received money

  * Make two modeling assumptions

    * The interval time v.s. The amount of money ⇒ ***No relationship***
    * The opening order v.s. The amount of money

      * Each order: The distribution of the amount of money satisfy ***skew distribution***
      * Each order: The conditional distribution of the amount of money satisfy ***uniform distribution***
draft: false
featured: false
authors:
  - admin
image:
  filename: featured.png
  focal_point: Smart
  preview_only: false
  caption: WeChat Red Envelope
---
## Summary

The prevalence of the online WeChat red packet has raised an attractive question of how to be the luckiest person (*i.e.*, get the most money). In this way, more and more people study which factors would affect the amount of money when opening the red packet. In this report, we focus on the relationship between the time to open the red packet and the amount of money. Specifically, we explore two factors of time, including interval time and order. Our experiments result show that only for each order,  the distribution and the conditional distribution of the amount of the money are closely to ***skew distribution*** and ***uniform distribution***, respectively. Moreover, our results also show that if you want to get more money you should take on some risks of getting less money at the same time.



## Key Words

WeChat red packet, expectation, variance, skew distribution, uniform distribution