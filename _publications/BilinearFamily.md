---
title: "Bilinear Exponential Family of MDPs: Frequentist Regret Bound with Tractable Exploration & Planning"
collection: publications
permalink: /publication/BilinearFamily
excerpt:
date: 2023-02-07
venue: 'The AAAI Conference on Artificial Intelligence'
paperurl: 
citation: 'Ouhamma, Reda, Debabrota Basu, and Odalric-Ambrym Maillard. "Bilinear exponential family of mdps: Frequentist regret bound with tractable exploration and planning." AAAI (2022).'
---

[Paper](http://redaouhamma.github.io/files/befrlsvi.pdf), [Poster](http://redaouhamma.github.io/files/befrlsviPoster.pdf)

   **Abstract**
We study the problem of episodic reinforcement learning in continuous state-action spaces with unknown rewards and
transitions. Specifically, we consider the setting where the rewards and transitions are modeled using parametric bilinear
exponential families. We propose an algorithm, BEF-RLSVI, that a) uses penalized maximum likelihood estimators to
learn the unknown parameters, b) injects a calibrated Gaussian noise in the parameter of rewards to ensure exploration,
and c) leverages linearity of the exponential family with respect to an underlying RKHS to perform tractable planning.
We further provide a frequentist regret analysis of BEF-RLSVI that yields an upper bound of Õ(\sqrt{d^3 H^3 K}), where d is
the dimension of the parameters, H is the episode length, and K is the number of episodes. Our analysis improves the
existing bounds for the bilinear exponential family of MDPs by \sqrt{H} and removes the handcrafted clipping deployed in
existing RLSVI-type algorithms. Our regret bound is order-optimal with respect to H and K.
