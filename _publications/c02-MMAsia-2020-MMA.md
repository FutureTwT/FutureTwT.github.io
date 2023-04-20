---
title: "Efficient Inter-image Relation Graph Neural Network Hashing for Scalable
Image Retrieval"
collection: publications
permalink: publications/IRGNNH
venue: 'ACM MMAsia'
year: 2021
paperurl: 'https://dl.acm.org/doi/10.1145/3444685.3446321'
codeurl: 'https://github.com/christinecui/IRGNNH'
authorlist: 'Hui Cui, Lei Zhu, Wentao Tan'
status: 'pub'
---

**Abstract:**
Unsupervised deep hashing is a promising technique for largescale image retrieval, as it equips powerful deep neural networks and has advantage on label independence. However, the unsupervised deep hashing process needs to train a large amount of deep neural network parameters, which is hard to optimize when no labeled training samples are provided. How to maintain the well scalability of unsupervised hashing while exploiting the advantage of deep neural network is an interesting but challenging problem to investigate. With the motivation, in this paper, we propose a simple but effective Inter-image Relation Graph Neural Network Hashing (IRGNNH) method. Different from all existing complex models, we discover the latent inter-image semantic relations without any manual labels and exploit them further to assist the unsupervised deep hashing process. Specifically, we first parse the images to extract latent involved semantics. Then, relation graph convolutional network is constructed to model the inter-image semantic relations and visual similarity, which generates representation vectors for image relations and contents. Finally, adversarial learning is performed to seamlessly embed the constructed relations into the image hash learning process, and improve the discriminative capability of the hash codes. Experiments demonstrate that our method significantly outperforms the state-of-the-art unsupervised deep hashing methods on both retrieval accuracy and efficiency.

**Download: [[PDF]](https://dl.acm.org/doi/10.1145/3444685.3446321)[[Code]](https://github.com/christinecui/IRGNNH)**
