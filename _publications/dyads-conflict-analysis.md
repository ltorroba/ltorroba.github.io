---
title: "Classifying Dyads for Militarized Conflict Analysis"
authors: "Niklas Stoehr, <b>Lucas Torroba Hennigen</b>, Samin Ahbab, Robert West, Ryan Cotterell"
state: published
collection: publications
permalink: /publication/dyads-conflict-analysis
excerpt: 'We compare dyadic and systemic correlates of conflict in terms of their ability to infer if two entities are allies or enemies. Our results suggests that our systemic features appear to be more correlated.'
date: 2021-11-07
venue: 'Proceedings of the 2021 Conference on Empirical Methods in Natural Language Processing'
short_venue: 'EMNLP'
paperurl: 'https://aclanthology.org/2021.emnlp-main.613.pdf'
codeurl: 'https://conflict-ai.github.io/conflictwiki'
---
Understanding the origins of militarized conflict is a complex, yet important undertaking. Existing research seeks to build this understanding by considering bi-lateral relationships between entity pairs (dyadic causes) and multi-lateral relationships among multiple entities (systemic causes). The aim of this work is to compare these two causes in terms of how they correlate with conflict between two entities. We do this by devising a set of textual and graph-based features which represent each of the causes. The features are extracted from Wikipedia and modeled as a large graph. Nodes in this graph represent entities connected by labeled edges representing ally or enemy-relationships. This allows casting the problem as an edge classification task, which we term dyad classification. We propose and evaluate classifiers to determine if a particular pair of entities are allies or enemies. Our results suggest that our systemic features might be slightly better correlates of conflict. Further, we find that Wikipedia articles of allies are semantically more similar than enemies.
