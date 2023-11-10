---
title: "Generalizing Backpropagation for Gradient-based Interpretability"
authors: "Kevin Du, <b>Lucas Torroba Hennigen</b>, Niklas Stoehr, Alexander Warstadt, Ryan Cotterell"
state: published
collection: publications
permalink: /publication/semiring-backprop
excerpt: 'By viewing backpropagation as a particular instance of a semiring algorithm, we explore its generalization to other semirings as a tool for interpretability.'
date: 2023-07-13
venue: 'Proceedings of the 61st Annual Meeting of the Association for Computational Linguistics'
short_venue: 'ACL'
paperurl: 'https://arxiv.org/pdf/2307.03056.pdf'
---
Many popular feature-attribution methods for interpreting deep neural networks rely on computing the gradients of a model's output with respect to its inputs. While these methods can indicate which input features may be important for the model's prediction, they reveal little about the inner workings of the model itself. In this paper, we observe that the gradient computation of a model is a special case of a more general formulation using semirings. This observation allows us to generalize the backpropagation algorithm to efficiently compute other interpretable statistics about the gradient graph of a neural network, such as the highest-weighted path and entropy. We implement this generalized algorithm, evaluate it on synthetic datasets to better understand the statistics it computes, and apply it to study BERT's behavior on the subject-verb number agreement task.
