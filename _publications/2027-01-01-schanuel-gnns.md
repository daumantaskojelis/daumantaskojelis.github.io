---
title: "Constant-Depth Rational-Weight GNNs and their Connection to Schanuel's Conjecture"
collection: publications
category: 'Conference Paper'
permalink: /publication/2027-01-01-gnns-and-schanuels-conjecture
excerpt: "We study the relationship between Schanuel's conjecture and the uniform expressive power of GNNs with sigmoid, tanh, and related activation functions."
date: 2027-01-02
venue: 'Undergoing Peer Review'
#slidesurl: 'http://academicpages.github.io/files/slides1.pdf'
paperurl: 'https://arxiv.org/abs/2610.16993'
citation: 'Daumantas Kojelis, Carsten Lutz'
---

A landmark result states that the expressive power of graph neural networks (GNNs) is bounded from above by the 1-dimensional Weisfeiler-Leman (1-WL) test. We ask whether a constant-depth GNN can match the expressive power of 1-WL while using only rational weights. We prove that this is the case when Schanuel's conjecture, a famous open problem from transcendental number theory, is taken to be true. Our GNN construction works even with integer weights, and more generally with a broad range of rational weights. As the activation function, it may use logistic sigmoid, hyperbolic tangent, or related functions. It is uniform across all graph sizes. We also prove a partial converse: if a GNN with exponentiation, hyperbolic sine or hyperbolic cosine as activation matches the expressive power of the 1-WL test in a slightly more expressive setting where graphs may contain certain auxiliary vertices, then this implies Schanuel's conjecture restricted to the numbers that arise in computations of the GNN. We also conduct experiments showing that the constructed GNNs indeed match the 1-WL test. 