---
title: "Learning to grow pretrained models for efficient transformer training"
authors: "Peihao Wang, Rameswar Panda, <b>Lucas Torroba Hennigen</b>, Philip Greengard, Leonid Karlinsky, Rogerio Feris, David Daniel Cox, Zhangyang Wang, Yoon Kim"
state: published
collection: publications
permalink: /publication/learning-to-grow-transformers
excerpt: 'We develop a technique to learn how to grow a pretrained model to a larger size, using the implicit knowledge in the parameters of the smaller model.'
date: 2023-05-01
venue: 'The Eleventh International Conference on Learning Representations'
short_venue: 'ICLR'
paperurl: 'https://arxiv.org/pdf/2303.00980'
codeurl: 'https://github.com/VITA-Group/LiGO'
---
Scaling transformers has led to significant breakthroughs in many domains, leading to a paradigm in which larger versions of existing models are trained and released on a periodic basis. New instances of such models are typically trained completely from scratch, despite the fact that they are often just scaled-up versions of their smaller counterparts. How can we use the implicit knowledge in the parameters of smaller, extant models to enable faster training of newer, larger models? This paper describes an approach for accelerating transformer training by learning to grow pretrained transformers, where we learn to linearly map the parameters of the smaller model to initialize the larger model. For tractable learning, we factorize the linear transformation as a composition of (linear) width- and depth-growth operators, and further employ a Kronecker factorization of these growth operators to encode architectural knowledge. Extensive experiments across both language and vision transformers demonstrate that our learned Linear Growth Operator (LiGO) can save up to 50% computational cost of training from scratch, while also consistently outperforming strong baselines that also reuse smaller pretrained models to initialize larger models.