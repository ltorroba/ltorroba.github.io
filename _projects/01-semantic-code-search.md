---
title: "Semantic Code Search"
excerpt: "For the course <i>Machine Learning for Programming</i> at Cambridge, I proposed a neural re-ranking model to improve results of a robust baseline for semantic code search, a retrieval task where a code snippet must be found given a particular natural language query."
image: "/images/500x300.png"
collection: projects
---

![alt text](../../files/architecture-overview.png "Logo Title Text 1")

For the course _Machine Learning for Programming_ at Cambridge, I proposed a neural re-ranking model to improve results of a robust baseline for semantic code search (SCS), a retrieval task where a code snippet must be found given a particular natural language query.
Specifically, I proposed an architecture where [ElasticSearch](https://www.elastic.co/) rankings, which have been shown to be a strong baseline for SCS ([Sachdev et al., 2018](https://dl.acm.org/doi/10.1145/3211346.3211353)), are improved using a neural system that is trained to re-rank them.
Results were promising, though further work is needed to determine if this holds using more established benchmarks (e.g., which use user queries instead of comments).
Nonetheless, it was a nice opportunity to explore graph neural networks ([Li et al., 2016](https://arxiv.org/abs/1511.05493); [Fernandes et al., 2019](https://arxiv.org/abs/1811.01824)) to obtain code-snippet-level representations of code, in a setting slightly different to natural language.

Happy to share the report and code upon request.
