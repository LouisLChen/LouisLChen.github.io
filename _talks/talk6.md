---
title: "Distributionally Robust Max Flow"
collection: talks
type: "Talk"
permalink: /talks/2018-11-06-talk-5
venue: "INFORMS Annual Meeting (2018)"
date: 2018-11-06
location: "Phoenix, Arizona"
---
In this talk, we consider the problem of distributionally robust network design. In this problem, the decision maker is to decide on the prepositioning of resources on arcs in a given s-t flow network in anticipation of an adversary’s selection of a probability distribution for the arc capacities, aimed to minimize the expected max flow. The adversary’s selection is limited to those distributions that are couplings of given arc capacity distributions, one for each arc. We show that we can efficiently solve the distributionally robust network design problem in the case of finite-supported marginals. Further, we take advantage of the network setting to efficiently solve for the distribution the adversary responds with. The primal-dual formulation of our previous work takes on a striking form in this study. As one might expect, the form relates to the well-known Max Flow, Min-Cut theorem. And this leads to the intriguing interpretation as a 2-player, zero-sum game wherein player 1 chooses what to set the arc capacities to and player 2 chooses an s-t cut. Essential to our analysis is the finding that the problem of finding the worst-case coupling of the stochastic arc capacities amounts to finding a distribution over the set of s-t cuts- this distribution being among the mixed strategies that player 2 would play in a Nash equilibrium. Furthermore, the support of such a distribution is a nested collection of s-t cuts, which implies an efficiently sized solution. 
