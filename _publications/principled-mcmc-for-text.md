---
title: "Principled Gradient-based Markov Chain Monte Carlo for Text Generation"
authors: "Li Du, Afra Amini, <b>Lucas Torroba Hennigen</b>, Xinyan Velocity Yu, Jason Eisner, Holden Lee, Ryan Cotterell"
state: preprint
collection: publications
permalink: /publication/principled-mcmc-for-text
excerpt: 'We show that previous gradient-based sampling methods for text generation are unfaithful to the true target distribution, and propose faithful alternatives.'
date: 2023-12-29
venue: 'arXiv'
short_venue: 'arXiv'
paperurl: 'https://arxiv.org/pdf/2312.17710.pdf'
---
Recent papers have demonstrated the possibility of energy-based text generation by adapting gradient-based sampling algorithms, a paradigm of MCMC algorithms that promises fast convergence. However, as we show in this paper, previous attempts on this approach to text generation all fail to sample correctly from the target language model distributions. To address this limitation, we consider the problem of designing text samplers that are faithful, meaning that they have the target text distribution as its limiting distribution. We propose several faithful gradient-based sampling algorithms to sample from the target energy-based text distribution correctly, and study their theoretical properties. Through experiments on various forms of text generation, we demonstrate that faithful samplers are able to generate more fluent text while adhering to the control objectives better.
