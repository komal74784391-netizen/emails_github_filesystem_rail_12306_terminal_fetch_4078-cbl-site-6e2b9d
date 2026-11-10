---
title: "Adaptive Token Pruning for Multimodal Retrieval"
collection: publications
category: conferences
permalink: /publication/adaptive-token-pruning
excerpt: "A budget-aware pruning scheme for image-text retrieval that keeps only the tokens that matter for the cross-modal similarity."
date: 2024-10-28
venue: "ACM International Conference on Multimedia (ACM MM 2024)"
paperurl: "https://doi.org/10.1145/3664647.3681032"
citation: "Bennett, C., Okafor, R., and Sato, H. (2024). Adaptive Token Pruning for Multimodal Retrieval. In Proceedings of the 32nd ACM International Conference on Multimedia (ACM MM 2024)."
codeurl: "https://github.com/mlingroup/atp-code"
---

Cross-modal retrievers waste computation on background patches and filler words. We learn a per-query token budget and prune both modalities before the fusion layers, improving retrieval throughput without hurting Recall@1.
