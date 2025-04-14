---
title: "On the Duality between Gradient Transformations and Adapters"
authors: "<b>Lucas Torroba-Hennigen</b>, Hunter Lang, Han Guo, Yoon Kim"
state: preprint
collection: publications
permalink: /publication/duality-gradients-adapters
excerpt: 'We explore a relationship between training with gradient transformations and with one-sided adapters, and use it to derive more memory-efficient single-node and distributed pretraining methods.'
date: 2025-02-19
venue: 'arXiv'
short_venue: 'arXiv'
paperurl: 'https://arxiv.org/pdf/2502.13811'
---
We study memory-efficient optimization of neural networks with linear gradient transformations, where the gradients are linearly mapped to a lower dimensional space than the full parameter space, thus saving memory required for gradient accumulation and optimizer state persistence. The model parameters are updated by first performing an optimization step in the lower dimensional space and then going back into the original parameter space via the linear map's transpose. We show that optimizing the model in this transformed space is equivalent to reparameterizing the original model through a linear adapter that additively modifies the model parameters, and then only optimizing the adapter's parameters. When the transformation is Kronecker-factored, this establishes an equivalence between GaLore and one-sided LoRA. We show that this duality between gradient transformations and adapter-based reparameterizations unifies existing approaches to memory-efficient training and suggests new techniques for improving training efficiency and memory use.