---
title: "Learning Value Functions in Deep Policy Gradients using Residual Variance"
collection: publications
permalink: /publication/LearningValueFunctions
excerpt: 'This paper is about the number 3'
date: 2021-05-03
venue: 'International Conference on Learning Representations (2021)'
paperurl: 'http://redaouhamma.github.io/files/avec.pdf'
citation: 'Flet-Berliac, Y., Ouhamma, R., Maillard, O. A., & Preux, P. (2020). "Learning value functions in deep policy gradients using residual variance." International Conference on Learning Representations. 2021.'
---
Policy gradient algorithms have proven to be successful in diverse decision making and control tasks. However, these methods suffer from high sample complexity and instability issues. In this paper, we address these challenges by providing a different approach for training the critic in the actor-critic framework. Our work builds on recent studies indicating that traditional actor-critic algorithms do not succeed in fitting the true value function, calling for the need to identify a better objective for the critic. In our method, the critic uses a new state-value (resp. state-action-value) function approximation that learns the value of the states (resp. state-action pairs) relative to their mean value rather than the absolute value as in conventional actor-critic. We prove the theoretical consistency of the new gradient estimator and observe dramatic empirical improvement across a variety of continuous control tasks and algorithms. Furthermore, we validate our method in tasks with sparse rewards, where we provide experimental evidence and theoretical insights.

[Paper](http://redaouhamma.github.io/files/avec.pdf), [Poster](http://redaouhamma.github.io/files/avecPoster.pdf)
