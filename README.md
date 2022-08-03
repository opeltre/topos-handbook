[topos]: https://github.com/opeltre/topos
[I]:     I_Sheaves_Functors.ipynb
[II]:    II_Graph_Convolution.ipynb
[III]:   III_Equivariant_MPNN.ipynb
[IV]:    IV_Belief_Networks.ipynb

# Topos Handbook

This repository is meant as a collection of notebooks, 
introducing diverse concepts from category theory and 
algebraic topology using (and used by) the [topos] library. 

The focus remains on introducing applications and 
showing how to build example models as promptly as possible, 
and this handbook might not substitute for precise 
texts on the subjects. 
We therefore tried to give appropriate references when relevant. 

## Introduction

The concepts of categories and functors,  
originating from algebraic topology ([Maclane Eilenberg, 1945]), 
have since become ubiquitous in computer science and mathematics. 
We begin with a quick introduction on the subject in ([I]). 

The simplest kind of structure [topos] implements is that of 
traditionnal 1-graphs, which we may 
also call 1-dimensional simplicial complexes. 
We show in ([II]) how graph convolutional networks (GCNs) 
can be designed using the natural harmonic structure on `Complex` 
instances.

An application of interest to us concerns 
message-passing neural networks (MPNNs) 
designed for us chemical materials and molecules. 
We show in ([III]) how one can enforce invariance and equivariance 
properties of such networks 
using natural transformations of $Euc(d)$-sheaves.

Finally, we describe general statistical systems as they occur
in thermodynamics. The laws of Boltzmann, 
although a couple centuries old, describe a great number of 
(almost) synonymous models used in machine learning and statistics: 
Boltzmann machines, graphical models, belief networks, energy based models, 
Markov random fiels... 
The generalized belief propagation algorithm (GBP) 
introduced in (Yedidia Freeman Weiss 2005), is a
message-passing algorithm providing a
powerful tool to estimate the statistics of such models 
and compute local approximations of global functionals.
We introduce GBP and its variants in [IV]

## Contents 

- [I-Sheaves and Functors][I]
- [II-Graph Convolutional Networks][II]
- [III-Equivariant Message-Passing for Materials and Molecules][III]
- [IV-Graphical Models, Boltzmann Machines and Belief Networks][IV]
