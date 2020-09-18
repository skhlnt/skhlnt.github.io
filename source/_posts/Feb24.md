---
title: Feb24-2019
date: 2019-02-24 19:46:59
tags: [笔记]
---

Today I read a 2006 article by JP Sethna's group talking about the predetermined "sloppiness" of models, which means that in many models plenty of parameters could be largely varied without producing any apparent changes to the models' results, which may rely delicately on other parameters.

<!--more-->

Given a suitable cost with respect to the parameters, the eigenvalues of the Hessian of the cost could be used to find the "stiff" and "sloppy" directions. Sloppy models are those with constant gaps between the logs of the eigenvalues.

Several examples were used to show stiff and sloppy models.

The author strengthened that the origin of sloppiness is 

> not a simple lack of data where trivial overparametrization leads to unidentifiable parameters.

but a character of (especially complex) systems.

Under some strong assumptions of L2 loss and symmetry of the parameters, the author formed the Hessian with the Vandermonde matrix, which brought upon the character of evenly spread eigenvalues in logarithm. 

It is useful to develop the decomposition algorithm of real world systems to Vandermonde subsystems.

https://journals.aps.org/prl/abstract/10.1103/PhysRevLett.97.150601