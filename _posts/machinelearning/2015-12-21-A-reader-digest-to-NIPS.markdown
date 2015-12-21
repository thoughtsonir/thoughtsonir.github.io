---
layout: article
title:  A reader's digest to NIPS 2015
date:   2015-12-21
categories: [machinelearning]
image:
    teaser: NIPS.png
author: mathieu_andreux
---
I attended [NIPS][nips] two weeks ago, as it took place in Montréal from the 7th to the 12th of December.
It was huge: according to the chairs, the number of attendees rose by 40% in one year, leading to about 3500 people.
Yet, it did not feel crowded, thanks to the very effective organization of Montréal's Palais des congrès. 

<img src="/images/nips15_attendance.png"/>

Deep learning was the key point at this conference: although only 10% of papers were primarily concerned by deep learning, a lot of optimization and Bayesian optimization papers were related to deep learning in some way or another.
As Zoubin Gharamani pointed out, the field is in a situation analogous to the one which prevailed 25 years ago, in the early 90s: neural networks were flourishing, a lot of efforts were devoted to training them, SVM were only being invented. 
In between, we have obtained a better understanding of what statistical learning means.
Instead of finding the best architecture to do stuff, I think it's high time we understand what "deep" learning means before going any further in this direction.

<h2>Some interesting papers</h2>

Here are some papers that I found interesting at this conference, mainly revolving around deep learning. I tried to group them by categories, although some of them could be attached to multiple categories:

<h4>Phase retrieval</h4>

[Solving Random Quadratic Systems of Equations is Nearly as Easy as Solving Linear Systems][phase1]

[Efficient Compressive Phase Retrieval with Constrained Sensing Vectors][phase2]

<h4>Attention models, more and more endowed with memory</h4>
[Attention-Based Models for Speech Recognition][attention1] 

[End-To-End Memory Networks][attention2]

[Inferring Algorithmic Patterns with Stack-Augmented Recurrent Nets][attention3]

[Pointer Networks][attention4]

<h4>Deep generative models</h4>
[Learning Wake-Sleep Recurrent Attention Models][generative1]

[A Recurrent Latent Variable Model for Sequential Data][generative2]

[Deep Generative Image Models using a Laplacian Pyramid of Adversarial Networks][generative3]

[Deep Visual Analogy-Making][generative4]

[Generative Image Modeling using Spatial LSTMs][generative5]

[Training Restricted Boltzmann Machine via the Thouless-Anderson-Palmer Free Energy][generative6]

<h4>Optimization for Neural Networks</h4>
[Beyond Convexity: Stochastic Quasi-Convex Optimization][optim1]

[Learning both Weights and Connections for Efficient Neural Network][optim2]

[Probabilistic Line Searches for Stochastic Optimization][optim3]

<h4>Towards more and more complex networks (gates, recurrent connections, intermediate modules)</h4>
[Parallel Multi-Dimensional LSTM, With Application to Fast Biomedical Volumetric Image Segmentation][complex1]

[Convolutional Neural Networks with Intra-Layer Recurrent Connections for Scene Labeling][complex2]

[Training Very Deep Networks][complex3]

[Spatial Transformer Networks][complex4]

<h4>Group invariance</h4>
[Learning with Group Invariant Features: A Kernel Perspective][group1]

<h2>The future of AI</h2>
It appears that AI is once again a [hype][neil_lawrence_hype] keyword.
In some aspects, it actually looks like we're in a science-fiction movie.
This topic was particularly discussed at the Symposium "Brains, Minds and Machines", which was chaired by Tomaso Poggio.

In general, at the conference, algorithmic issues were mainly discussed. AI is seen as a superstructure, independent of the material upon which it is built. I don't know if it's true or not; however, I think that NIPS - Neural Information Processing Systems - was partly founded in order to build machines inspired by biology, so-called "neuromorphic computing". In this regard, the [paper by IBM researchers][truenorth] on how to train their True North chip was particularly relevant and interesting. For embedded technology, future probably lies in this direction.

When it comes to higher order cognitive capabilities, Joshua Tenenbaum presented a [recent work][tenenbaum] done in collaboration with deep learning people, which was pretty impressive. They developed a hierarchical generative model aimed at zero-shot learning. When presented a single instance of a foreign character, the computer is able to reproduce and recognize multiple examples of this character, with performances quite comparable to humans. Tenenbaum insisted on the forecoming meeting of cognitive reasoning with deep learning perception, and I think he might be right.

At the end of NIPS, the [OpenAI][openai] initiative was announced. Funded by private donors (notably Elon Musk and Peter Thiel), it will be an open research lab focused on AI technology. I think it's a very nice initiative, and another indicator of how hot the field is (the pledges involve around $1B). Let's see what it gives!


[nips]: http://nips.cc/
[neil_lawrence_hype]: http://inverseprobability.com/2015/12/13/hype/
[openai]: https://openai.com
[phase1]: https://papers.nips.cc/paper/5743-solving-random-quadratic-systems-of-equations-is-nearly-as-easy-as-solving-linear-systems
[phase2]: https://papers.nips.cc/paper/6021-efficient-compressive-phase-retrieval-with-constrained-sensing-vectors
[attention1]: https://papers.nips.cc/paper/5847-attention-based-models-for-speech-recognition
[attention2]: https://papers.nips.cc/paper/5846-end-to-end-memory-networks
[attention3]: https://papers.nips.cc/paper/5857-inferring-algorithmic-patterns-with-stack-augmented-recurrent-nets
[attention4]: https://papers.nips.cc/paper/5866-pointer-networks
[generative1]: https://papers.nips.cc/paper/5861-learning-wake-sleep-recurrent-attention-models
[generative2]: https://papers.nips.cc/paper/5653-a-recurrent-latent-variable-model-for-sequential-data
[generative3]: https://papers.nips.cc/paper/5773-deep-generative-image-models-using-a-laplacian-pyramid-of-adversarial-networks
[generative4]: https://papers.nips.cc/book/advances-in-neural-information-processing-systems-28-2015
[generative5]: https://papers.nips.cc/paper/5637-generative-image-modeling-using-spatial-lstms
[generative6]: https://papers.nips.cc/paper/5788-training-restricted-boltzmann-machine-via-the-thouless-anderson-palmer-free-energy
[optim1]: https://papers.nips.cc/paper/5718-beyond-convexity-stochastic-quasi-convex-optimization
[optim2]: https://papers.nips.cc/paper/5784-learning-both-weights-and-connections-for-efficient-neural-network
[optim3]: https://papers.nips.cc/paper/5753-probabilistic-line-searches-for-stochastic-optimization
[complex1]: https://papers.nips.cc/paper/5642-parallel-multi-dimensional-lstm-with-application-to-fast-biomedical-volumetric-image-segmentation
[complex2]: https://papers.nips.cc/paper/5634-convolutional-neural-networks-with-intra-layer-recurrent-connections-for-scene-labeling
[complex3]: https://papers.nips.cc/paper/5850-training-very-deep-networks
[complex4]: https://papers.nips.cc/paper/5854-spatial-transformer-networks
[group1]: https://papers.nips.cc/paper/5798-learning-with-group-invariant-features-a-kernel-perspective
[truenorth]: https://papers.nips.cc/paper/5862-backpropagation-for-energy-efficient-neuromorphic-computing
[tenenbaum]: http://www.sciencemag.org/content/350/6266/1332.full