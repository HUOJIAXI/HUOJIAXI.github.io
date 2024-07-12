---
title: "Multi-Robot Path Planning in Narrow Warehouse Environments with Fast Feasibility Heuristics"
collection: publications
permalink: /publication/2024-02-17-paper-title-number-4
excerpt: 'This paper is indexed by EI.'
date: 2022-10-11
venue: '41st Chinese Control Conference (CCC)'
paperurl: 'http://huojiaxi.github.io/files/paper1.pdf'
citation: 'Huo J, Zheng R, Zhang S, et al. Multi-Robot Path Planning in Narrow Warehouse Environments with Fast Feasibility Heuristics[C]//41st Chinese Control Conference (CCC). IEEE, 2022: 1840-1845.'
---

In this paper, we present a novel method for solving the multi-robot path planning problem in narrow warehouse
environments. Robots may have to be operated in close proximity to each other in narrow lanes between pod clusters, which
challenges robot-robot collision avoidance. This motivates us to consider an efficient algorithm to generate collision-free robot
paths in narrow warehouse environments. The algorithm builds a two-stage scheme based on integer programming: (i) multi-robot path planning under one-way constraints; and (ii) fast feasibility heuristics. The developed algorithm has two advantages:
(i) the proposed scheme successfully avoids the situation where the robots collide in narrow lanes; and (ii) by using the fast feasibility heuristics which replaces the integer programming solver’s built-in feasibility heuristics, the feasibility heuristics’ running
time can be effectively reduced while producing better initial feasible solutions for the integer programming model solving process. Compared with the existing optimal, sub-optimal, and polynomial-complexity algorithms, our developed algorithm can
leverage the advantage of integer programming to effectively reach a balance between running time and optimality in narrow
warehouse environments. This point is demonstrated in the simulations.
