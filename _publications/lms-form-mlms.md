---
title: "Deriving Language Models from Masked Language Models"
authors: "<b>Lucas Torroba Hennigen</b>, Yoon Kim"
state: published
collection: publications
permalink: /publication/lms-from-mlms
excerpt: 'We explore and benchmark ways of deriving a joint distribution from the unary conditionals specified by a masked language model.'
date: 2023-07-14
venue: 'Proceedings of the 61st Annual Meeting of the Association for Computational Linguistics'
short_venue: 'ACL'
paperurl: 'https://arxiv.org/pdf/2305.15501.pdf'
codeurl: 'https://github.com/ltorroba/lms-from-mlms'
---
Masked language models (MLM) do not explicitly define a distribution over language, i.e., they are not language models per se. However, recent work has implicitly treated them as such for the purposes of generation and scoring. This paper studies methods for deriving explicit joint distributions from MLMs, focusing on distributions over two tokens, which makes it possible to calculate exact distributional properties. We find that an approach based on identifying joints whose conditionals are closest to those of the MLM works well and outperforms existing Markov random field-based approaches.
