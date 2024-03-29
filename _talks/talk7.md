---
title: "Distributionally Robust Influence Maximization"
collection: talks
type: "Talk"
permalink: /talks/2018-11-06-talk-7
venue: "IFORS 2021"
date: 2021-08-23
location: "Online"
---
We propose and study a distributionally robust influence maximization problem. Unlike the classic Independent Cascade model proposed
in Kempe, Kleinberg, and Tardos (2003), we consider a model that
involves an adversarial response to the selection of seed set. More
precisely, rather than the spread of influence being determined by the
independent coupling of random arcs, the spread of influence will be
determined by an adversarial coupling of random arcs in response to
any selection of seed set. Similarly to traditional stochastic models, the
optimization problem remains NP-Hard. However, in contrast, with
this newly introduced robust model, both the influence function and
any node’s likelihood of being influenced can now be efficiently computed; furthermore, we show that even with an adversarial coupling,
the greedy algorithm still guarantees a (1 - 1/e) - approximation of the
optimum, as in the Independent Cascade model. Finally, we consider
computational comparisons through experiments.
