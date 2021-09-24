---
title: "Intrinsic Probing Through Dimension Selection"
authors: "<b>Lucas Torroba Hennigen</b>, Adina Williams, Ryan Cotterell"
state: published
collection: publications
permalink: /publication/2020-emnlp-intrinsic-probing
excerpt: 'We introduce a novel framework for intrinsic probing that leverages a decomposable multivariate Gaussian probe. We run experiments on 36 languages from the Universal Dependencies treebanks, and find that fastText concentrates its linguistic structure more than BERT.'
date: 2020-11-01
venue: 'Proceedings of the 2020 Conference on Empirical Methods in Natural Language Processing'
short_venue: 'EMNLP 2020'
paperurl: 'https://arxiv.org/abs/2010.02812'
codeurl: 'https://github.com/rycolab/intrinsic-probing'
---
Most modern NLP systems make use of pre-trained contextual representations that attain astonishingly high performance on a variety of tasks. Such high performance should not be possible unless some form of linguistic structure inheres in these representations, and a wealth of research has sprung up on probing for it. In this paper, we draw a distinction between intrinsic probing, which examines how linguistic information is structured within a representation, and the extrinsic probing popular in prior work, which only argues for the presence of such information by showing that it can be successfully extracted. To enable intrinsic probing, we propose a novel framework based on a decomposable multivariate Gaussian probe that allows us to determine whether the linguistic information in word embeddings is dispersed or focal. We then probe fastText and BERT for various morphosyntactic attributes across 36 languages. We find that most attributes are reliably encoded by only a few neurons, with fastText concentrating its linguistic structure more than BERT.

<a class="link-button paper-button" href="https://www.aclweb.org/anthology/2020.emnlp-main.15.pdf">Paper</a>
<a class="link-button code-button" href="https://github.com/rycolab/intrinsic-probing">Code</a>
