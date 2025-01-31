---
title: "Partial Multi-Modal Hashing via Neighbor-aware Completion Learning"
collection: publications
permalink: publications/NCH
venue: 'IEEE TMM'
year: 2023
paperurl: 'https://ieeexplore.ieee.org/document/10021860'
codeurl: 'https://github.com/FutureTwT/NCH'
authorlist: 'Wentao Tan, Lei Zhu, Jingjing Li, Zheng Zhang, Huaxiang Zhang'
status: 'pub'
---

**Abstract:**

Multi-modal hashing technology can support large-scale multimedia retrieval well, because of its fast query speed and low storage consumption. Although many multi-modal hashing methods have been developed in the literature, they still suffer from three important problems: 1) Most multi-modal hashing methods assume that multi-modal data are complete. This ideal assumption limits their application to practical retrieval scenarios, where the modality-missing is common. 2) Existing partial multi-modal hashing methods directly model incomplete multi-modal data for hash learning, which may result in partial multi-modal semantics in the learned hash codes. 3) Most of the methods are based on the shallow learning framework, which inevitably suffers from limited representation capability. To solve the above problems, we propose a flexible deep partial multi-modal hash learning framework, named Neighbor-aware Completion Hashing (NCH). Our framework jointly performs the cross-modal completion learning for incomplete multi-modal data and the multi-modal hash learning. It can not only support model training with incomplete multi-modal data but also handle incomplete multi-modal queries. Besides, we design a neighbor-aware completion learning module to capture neighbor semantics and generate distribution-consistent completed features. Finally, we conduct extensive experiments to evaluate our method on both fully-paired and partial multi-modal retrieval scenarios. The experimental results verify the superiority of our proposed method over the state-of-the-art baselines. 

**Download: [[PDF]](https://ieeexplore.ieee.org/document/10021860)[[Code]](https://github.com/FutureTwT/NCH)**
