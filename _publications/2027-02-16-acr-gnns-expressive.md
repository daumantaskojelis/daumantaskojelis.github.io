---
title: "Understanding the Expressive Power of GNNs with Global Readout"
collection: publications
category: 'Conference Paper'
permalink: /publication/2027-01-01-acr-gnn-logical-characterisation
excerpt: 'We study the logical expressive power of GNNs with global readout, finding the limit to which C^2 can be used for characterisations'
date: 2027-01-01
venue: 'Undergoing Peer Review'
#slidesurl: 'http://academicpages.github.io/files/slides1.pdf'
paperurl: 'https://arxiv.org/abs/2604.22870'
citation: 'Maurice Funk, Daumantas Kojelis'
---

We study the expressive power of message-passing aggregate-combine-readout graph neural networks (ACR-GNNs).
Particularly, we focus on the first-order (FO) properties expressible
by this formalism.
While a tight logical characterisation remains a difficult
open question, we make two contributions towards answering it.
First, we show that standard sum aggregation and readout suffice for GNNs to
capture FO properties that cannot be expressed in the logic
$$C^2$$ on both directed and undirected graphs. This strengthens known
results where aggregation and readout functions are specially crafted for the task.
Second, we identify two natural ways of restoring characterisability (with regard to $$C^2$$) for ACR-GNNs.
One option is to limit local aggregation without imposing restrictions on global readout, whilst
the second is to run ACR-GNNs over graphs of bounded degree but unbounded size.
In both cases, the FO properties captured by GNNs are exactly
those definable by graded modal logic with global counting modalities.
Our results thus establish an innate lower and upper bound in terms of how far fragments of $$C^2$$ can be
taken to characterise GNNs, and imply that it is indeed the unbounded interaction of aggregation and readout that
pushes the logical expressive power of GNNs outside $$C^2$$.