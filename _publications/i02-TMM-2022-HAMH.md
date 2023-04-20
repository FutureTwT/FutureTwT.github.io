---
title: "Teacher-Student Learning: Efficient Hierarchical Message Aggregation Hashing for Cross-Modal Retrieval"
collection: publications
permalink: publications/HMAH
venue: 'IEEE TMM'
year: 2022
paperurl: 'https://ieeexplore.ieee.org/document/9782694'
codeurl: 'https://github.com/FutureTwT/HMAH'
authorlist: 'Wentao Tan, Lei Zhu, Jingjing Li, Huaxiang Zhang, Junwei Han'
status: 'pub'
---

**Abstract:**

Inspired by the powerful representation capability of deep neural networks, deep cross-modal hashing methods have recently drawn much attention and various deep cross-modal hashing methods have been developed. However, two key problems have not been solved well yet: 1) With advanced neural network models, how to seek the multi-modal alignment space which can effectively model the intrinsic multi-modal correlations and reduce the heterogeneous modality gaps. 2) How to effectively and efficiently preserve the modelled multi-modal semantic correlations into the binary hash codes under the deep learning paradigm. In this paper, we propose a \emph{Hierarchical Message Aggregation Hashing} (HMAH) method within an efficient teacher-student learning framework. Specifically, on the teacher end, we develop hierarchical message aggregation networks to construct a multi-modal complementary space by aggregating the semantic messages hierarchically across different modalities, which can better align the heterogeneous modalities and model the fine-grained multi-modal correlations. On the student end, we train a couple of student modules that learn hash functions to support cross-modal retrieval. We design a cross-modal correlation knowledge distillation strategy which seamlessly transfers the modelled fine-grained multi-modal semantic correlations from the teacher to the lightweight student modules. With the fine-grained knowledge supervision from teacher module, the semantic representation capability of hash functions can be enhanced. In addition, the whole learning framework avoids the time-consuming finetuning on the pre-trained deep models as existing methods and it is computationally efficient. Experimental results demonstrate the significant performance improvement of the proposed method on both retrieval accuracy and efficiency, compared with the state-of-the-art deep cross-modal hashing methods. 

**Download: [[PDF]](https://ieeexplore.ieee.org/document/9782694)[[Code]](https://github.com/FutureTwT/HMAH)**
