---
title: "Towards Verifiable Text Generation with Symbolic References"
authors: "<b>Lucas Torroba Hennigen&ast;</b>, Shannon Shen&ast;, Aniruddha Nrusimha, Bernhard Gapp, David Sontag, Yoon Kim"
state: preprint
collection: publications
permalink: /publication/symgen
excerpt: 'We develop a method for more verifiable text generation by prompting LLMs to generate their output using symbolic references into some source data.'
date: 2023-11-15
venue: 'arXiv'
short_venue: 'arXiv'
paperurl: 'https://arxiv.org/pdf/2311.09188.pdf'
---
Large language models (LLMs) have demonstrated an impressive ability to synthesize plausible and fluent text. However they remain vulnerable to hallucinations, and thus their outputs generally require manual human verification for high-stakes applications, which can be time-consuming and difficult. This paper proposes symbolically grounded generation (SymGen) as a simple approach for enabling easier validation of an LLM's output. SymGen prompts an LLM to interleave its regular output text with explicit symbolic references to fields present in some conditioning data (e.g., a table in JSON format). The references can be used to display the provenance of different spans of text in the generation, reducing the effort required for manual verification. Across data-to-text and question answering experiments, we find that LLMs are able to directly output text that makes use of symbolic references while maintaining fluency and accuracy.
