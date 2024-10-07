---
title: "Latte: Latent Attention for Linear Time Transformers"
collection: publications
category: manuscripts
permalink: /publication/2024-10-03-paper-title-number-1
excerpt: 'This paper is about a linear latent variable re-parametrisation of attention and combining it with local standard attention'
date: 2024-10-01
venue: 'NGSM ICML Workshop'
paperurl: 'https://arxiv.org/abs/2402.17512'
citation: 'Dolga, Rares, Marius Cobzarenco, and David Barber. "Latent Attention for Linear Time Transformers." arXiv preprint arXiv:2402.17512 (2024).'
---

The time complexity of the standard attention mechanism in transformers scales quadratically with sequence length. We propose a probabilistic framework for attention, enabling us to derive a novel low-rank linear re-parameterisation of both bidirectional and causal cases, based on defining a latent variable model. Our method can be seamlessly integrated as a drop-in replacement for the standard attention mechanism. Additionally, this framework provides a natural extension for combining local standard attention with our global linear attention. This approach allows us to extend the context length of existing large pre-trained models with only a few additional training steps. The resulting ``Latte Transformer'' achieves performance comparable to standard attention and other state-of-the-art models, while maintaining linear time and memory complexity, along with constant-time next-token prediction during inference.