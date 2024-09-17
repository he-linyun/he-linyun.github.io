---
title: "Stochastic Approximation for Multi-period Simulation Optimization with Streaming Input Data"
authors: '<b>Linyun He</b>, Uday V. Shanbhag, Eunhye Song'
collection: publications
permalink: /publication/2023-Multi-period-SA
date: 2024-04-30
venue: ACM Transactions on Modeling and Computer Simulation
venueType: journal
volume: 34
number: 2
page: 1-27
paperurl: 'https://dl.acm.org/doi/10.1145/3617595'
status: published
citation: aaa
---

## Abstract
We consider a continuous-valued simulation optimization (SO) problem, where a simulator is built to optimize an expected performance measure of a real-world system while parameters of the simulator are estimated from streaming data collected periodically from the system. At each period, a new batch of data is combined with the cumulative data and the parameters are re-estimated with higher precision. The system requires the decision variable to be selected in all periods. Therefore, it is sensible for the decision-maker to update the decision variable at each period by solving a more precise SO problem with the updated parameter estimate to reduce the performance loss with respect to the target system. We define this decision-making process as the multi-period SO problem and introduce a multi-period stochastic approximation (SA) framework that generates a sequence of solutions. Two algorithms are proposed: Re-start SA (<b>ReSA</b>) reinitializes the stepsize sequence in each period, whereas Warm-start SA (<b>WaSA</b>) carefully tunes the stepsizes, taking both fewer and shorter gradient-descent steps in later periods as parameter estimates become increasingly more precise. We show that under suitable strong convexity and regularity conditions, <b>ReSA</b> and <b>WaSA</b> achieve the best possible convergence rate in expected sub-optimality either when an unbiased or a simultaneous perturbation gradient estimator is employed, while <b>WaSA</b> accrues significantly lower computational cost as the number of periods increases. In addition, we present the <b>regularized ReSA</b> which obviates the need to know the strong convexity constant and achieves the same convergence rate at the expense of additional computation.
