---
title: "Bit-aware Semantic Transformer Hashing for Multi-modal Retrieval"
collection: publications
permalink: publications/BSTH
venue: 'ACM SIGIR'
year: 2022
paperurl: 'https://dl.acm.org/doi/10.1145/3477495.3531947'
codeurl: 'https://github.com/FutureTwT/BSTH'
authorlist: 'Wentao Tan, Lei Zhu, Weili Guan, Jingjing Li, Zhiyong Cheng'
status: 'pub'
---

**Abstract:**

Multi-modal hashing learns binary hash codes with extremely low storage cost and high retrieval speed. It can support efficient multi-modal retrieval well. However, most existing methods still suffer from three important problems: 1) Limited semantic representation capability with shallow learning. 2) Mandatory feature-level multi-modal fusion ignores heterogeneous multi-modal semantic gaps. 3) Direct coarse pairwise semantic preserving cannot effectively capture the fine-grained semantic correlations. For solving these problems, in this paper, we propose a \emph{Bit-aware Semantic Transformer Hashing} (BSTH) framework to excavate bit-wise semantic concepts and simultaneously align the heterogeneous modalities for multi-modal hash learning on the concept-level. Specifically, the bit-wise implicit semantic concepts are learned with the transformer in a self-attention manner, which can achieve implicit semantic alignment on the fine-grained concept-level and reduce the heterogeneous modality gaps. Then, the concept-level multi-modal fusion is performed to enhance the semantic representation capability of each implicit concept and the fused concept representations are further encoded to the corresponding hash bits via bit-wise hash functions. Further, to supervise the bit-aware transformer module, a label prototype learning module is developed to learn prototype embeddings for all categories that capture the explicit semantic correlations on the category-level by considering the co-occurrence priors. Experiments on three widely tested multi-modal retrieval datasets demonstrate the superiority of the proposed method from various aspects.

**Download: [[PDF]](https://dl.acm.org/doi/10.1145/3477495.3531947)[[Code]](https://github.com/FutureTwT/BSTH)**
