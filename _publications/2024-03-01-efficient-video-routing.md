---
title: "Sparse Attention Routing for Efficient Video Transformers"
collection: publications
category: manuscripts
permalink: /publication/efficient-video-routing
excerpt: "A differentiable routing layer that sparsifies attention across video tokens while preserving temporal grounding."
date: 2024-03-01
venue: "IEEE Transactions on Pattern Analysis and Machine Intelligence"
paperurl: "https://doi.org/10.1109/TPAMI.2024.3361201"
citation: "Bennett, C., Okafor, R., and Lindqvist, M. (2024). Sparse Attention Routing for Efficient Video Transformers. IEEE Transactions on Pattern Analysis and Machine Intelligence, 46(3), 1101-1116."
---

Video transformers spend most of their compute on redundant spatiotemporal tokens. We introduce a learned routing layer that merges tokens into a small set of routes and restores temporal alignment after attention. The resulting model matches dense baselines on three video benchmarks while using under half of the attention FLOPs.
