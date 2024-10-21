---
title: "Functional Autoencoder for Smoothing and Representation Learning"
authors : Sidi Wu, Cédric Beaulac and Jiguo Cao
collection: publications
permalink: /publication/FAE
status : Published
venue : Statistics and Computing
date: 2024-10-17
paperurl: 'https://arxiv.org/pdf/2401.09499.pdf'
---

Published in [Statistics and Computing](https://link.springer.com/journal/11222)

### Abstract :

*A common pipeline in functional data analysis is to first convert the discretely
observed data to smooth functions, and then represent the functions by a finitedimensional vector of coefficients summarizing the information. Existing methods
for data smoothing and dimensional reduction mainly focus on learning the linear mappings from the data space to the representation space, however, learning
only the linear representations may not be sufficient. In this study, we propose
to learn the nonlinear representations of functional data using neural network
autoencoders designed to process data in the form it is usually collected without the need of preprocessing. We design the encoder to employ a projection
layer computing the weighted inner product of the functional data and functional
weights over the observed timestamp, and the decoder to apply a recovery layer
that maps the finite-dimensional vector extracted from the functional data back
to functional space using a set of predetermined basis functions. The developed
architecture can accommodate both regularly and irregularly spaced data. Our
experiments demonstrate that the proposed method outperforms functional principal component analysis in terms of prediction and classification, and maintains
superior smoothing ability and better computational efficiency in comparison to
the conventional autoencoders under both linear and nonlinear settings.*

Download a pre-print of the paper [here](https://arxiv.org/pdf/2401.09499.pdf). You can find the finalized version of the paper [here](https://link.springer.com/article/10.1007/s11222-024-10501-w).
