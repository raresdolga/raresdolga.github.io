---
title: "RotRNN: Modelling Long Sequences with Rotations"
collection: publications
category: manuscripts
permalink: /publication/2024-10-02-paper-title-number-2
excerpt: 'This paper is about parameterising linear recursive neural networks with rotation matrices.'
venue: 'NGSM ICML Workshop'
date: 2024-10-01
paperurl: 'https://arxiv.org/abs/2407.07239'
citation: 'Dolga, Rares, et al. "RotRNN: Modelling Long Sequences with Rotations." arXiv preprint arXiv:2407.07239 (2024).'
---

Linear recurrent models, such as State Space Models (SSMs) and Linear Recurrent Units (LRUs), have recently shown state-of-the-art performance on long sequence modelling benchmarks. Despite their success, they come with a number of drawbacks, most notably their complex initialisation and normalisation schemes. In this work, we address some of these issues by proposing RotRNN -- a linear recurrent model which utilises the convenient properties of rotation matrices. We show that RotRNN provides a simple model with fewer theoretical assumptions than prior works, with a practical implementation that remains faithful to its theoretical derivation, achieving comparable scores to the LRU and SSMs on several long sequence modelling datasets.