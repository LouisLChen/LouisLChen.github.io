---
title: "Distributionally Robust Max Flows with Marginals"
collection: publications
permalink: /publication/2010-10-01-paper-title-number-2
excerpt: 'Consider an s-t flow network in which the arc capacities are distributed according to an unknown distribution, but with known marginals. We study the problem of finding a coupling of the marginals that yields the worst, expected Max-flow value. Towards solving this optimization problem, we identify a primal-dual formulation. As one might expect, the form relates to the well-known Max Flow, Min-Cut theorem. And this leads to the rather intriguing interpretation as a 2-player, zero-sum game wherein player 1 chooses what to set the arc capacities to and player 2 chooses an s-t cut. Our contributions in this talk are twofold: (1) we present a linear program (that is efficient with finite-supported marginals) that not only computes the worst-case expected value but is of a form amenable in a two-stage network design formulation, and (2) we show that the problem of finding the worst-case coupling of the stochastic arc capacities boils down to finding an optimal distribution
 over the set of s-t cuts, which we show can be found efficiently.'
date: 2020-10-01
venue: 'SOSA 2020'
paperurl: 'https://www.dropbox.com/s/z59207hnz3iihi0/ltexpprt.pdf?dl=0'
citation: 'Louis Chen, Will Ma, James Orlin, David Simchi-Levi. (2020). &quot;Distributionally Robust Max Flows with Marginals.&quot; <i>SOSA 2020</i>. 1(2).'
---
In this paper, we extend the study of Chen et al 2018 to the problem of distributionally robust network design. In this problem, the decision maker is to decide on the prepositioning of resources on arcs in a given s-t flow network in anticipation of an adversary's selection of a probability distribution for the arc capacities that seeks to minimize the expected max flow. The adversary's selection is limited to those distributions that are couplings of given arc capacity distributions, one for each arc. We find that modeling the uncertainty in this way is certainly more sensible than prescribing the stochastic behavior of the arc capacities across an entire network. Furthermore, while it is hard to compute even the expectation with respect to the independent coupling of the stochastic arc capacities, we show that we can efficiently solve the distributionally robust network design problem. Indeed, this particular problem satisfies the sufficiency condition for tractability that we proposed in the previous work. But what's more, a highlight and extension in this work is to take advantage of the network setting to go even further and efficiently solve for the distribution the adversary responds with.
[Download paper here](https://www.dropbox.com/s/z59207hnz3iihi0/ltexpprt.pdf?dl=0)

Recommended citation: Your Name, You. (2020). "Distributionally Robust Max Flows with Marginals." <i>SOSA 2020  1</i>. 1(2).
