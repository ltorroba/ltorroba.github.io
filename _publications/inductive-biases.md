---
title: "Probing as Quantifying the Inductive Bias of Pre-trained Representations"
authors: "Alexander Immer&ast;, <b>Lucas Torroba Hennigen&ast;</b>, Vincent Fortuin, Ryan Cotterell"
state: published
collection: publications
permalink: /publication/inductive-biases
excerpt: 'We propose a new method to evaluate the inductive biases of pre-trained NLP representations which addresses limitations of previous work in probing. Our results suggest that fastText may offer a better inductive bias than BERT in certain multilingual morphosyntactic tasks.'
date: 2022-05-22
venue: 'Proceedings of the 60th Annual Meeting of the Association for Computational Linguistics'
short_venue: 'ACL'
paperurl: 'https://aclanthology.org/2022.acl-long.129.pdf'
codeurl: 'https://github.com/rycolab/evidence-probing'
---
Pre-trained contextual representations have led to dramatic performance improvements on a range of downstream tasks. This has motivated researchers to quantify and understand the linguistic information encoded in them. In general, this is done by probing, which consists of training a supervised model to predict a linguistic property from said representations. Unfortunately, this definition of probing has been subject to extensive criticism, and can lead to paradoxical or counter-intuitive results. In this work, we present a novel framework for probing where the goal is to evaluate the inductive bias of representations for a particular task, and provide a practical avenue to do this using Bayesian inference. We apply our framework to a series of token-, arc-, and sentence-level tasks. Our results suggest that our framework solves problems of previous approaches and that fastText can offer a better inductive bias than BERT in certain situations.
