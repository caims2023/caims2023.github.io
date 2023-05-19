---
speakers:
  - Justin Wan
name: "Learning Volatility Surfaces using Generative Adversarial Networks"
categories:
  - Short Talks
hide: no
---
In this talk, we propose a generative adversarial network (GAN) approach for efficiently computing volatility surfaces. The idea is to make use of the special GAN neural architecture so that on one hand, we can learn volatility surfaces from training data and on the other hand, enforce no-arbitrage conditions. In particular, the generator network is assisted in training by a discriminator that evaluates whether the generated volatility matches the target distribution. Meanwhile, our framework trains the GAN network to satisfy the no-arbitrage constraints by introducing penalties as regularization terms. The proposed GAN model allows the use of shallow networks which results in much less computational costs. In our experiments, we demonstrate the performance of the proposed method by comparing with the state-of-the-art methods for computing implied and local volatility surfaces. We show that our GAN model can outperform artificial neural network (ANN) approaches in terms of accuracy and computational time.
