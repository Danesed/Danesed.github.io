---
title: "Attention is all you Need"
description: "Ashish Vaswani, Noam Shazeer, Niki Parmar, Jakob Uszkoreit, Llion Jones, Aidan N. Gomez, Łukasz Kaiser, Illia Polosukhin"
pubDate: "Sep 10 2022"
heroImage: "https://miro.medium.com/v2/resize:fit:863/0*jKqypwGzmDv7KDUZ.png"
badge: "NeurIPS"
tags: ["Transformers","Deep learning"]
---

The dominant sequence transduction models are based on complex recurrent or
convolutional neural networks that include an encoder and a decoder. The best
performing models also connect the encoder and decoder through an attention
mechanism. We propose a new simple network architecture, the Transformer,
based solely on attention mechanisms, dispensing with recurrence and convolutions
entirely. Experiments on two machine translation tasks show these models to
be superior in quality while being more parallelizable and requiring significantly
less time to train. Our model achieves 28.4 BLEU on the WMT 2014 Englishto-German translation task, improving over the existing best results, including
ensembles, by over 2 BLEU. On the WMT 2014 English-to-French translation task,
our model establishes a new single-model state-of-the-art BLEU score of 41.0 after
training for 3.5 days on eight GPUs, a small fraction of the training costs of the
best models from the literature.
