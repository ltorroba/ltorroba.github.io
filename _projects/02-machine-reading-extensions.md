---
title: "Re-ranking for Machine Reading"
excerpt: "For the <i>Machine Learning for Language Processing</i> course at Cambridge, I explored some extensions to our (then under-review) ACL 2020 paper \"Machine Reading of Historical Events.\" Apart from an empirical study of different attention mechanisms, I also explored how to cast this as a ranking problem. While improvements were modest in the setting we cared about, I found that this approach gave substantial improvements in a setting were we have a chronological ordering of events, but year annotations only for some of them."
image: "/images/500x300.png"
collection: projects
---

For the _Machine Learning for Language Processing_ course at Cambridge, I explored some extensions to our (then under-review) ACL 2020 paper "Machine Reading of Historical Events" ([Honovich et al., 2020](../../publication/2020-acl-machine-reading-historical-events)).
In that paper, we explore how to order historical events chronologically based on short textual descriptions of events and, optionally, some contextual information extracted from Wikipedia.

In my report, I conducted two sets of experiments.
The first consisted of adding attention to our architecture.
The second was exploring a ranking formulating of this task using RankNet ([Burges et al., 2005](https://doi.org/10.1145/1102351.1102363)).
Both of these gave mild performance improvements at best in the setting we cared about, however, I did find that if we only had year annotations for some datapoints, but a full chronological ordering of them, this approach netted more substantial improvements.

Happy to share the report and code upon request.
