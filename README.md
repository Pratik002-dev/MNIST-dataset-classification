# MNIST-dataset-classification
In this project, we are training the images in MNIST (Handwritten digit image dataset) Dataset using a deep learning based neural network called GAN (Generative Adversarial Network) so that the model will accurately recognise the handwritten digits.
GANs have two main blocks(two neural networks) which compete with each other and are able to capture, copy, and analyze the variations in a dataset. The two models are usually called Generator and Discriminator which we will cover in Components on GANs. To understand the term GAN let’s break it into separate three parts

Generative – To learn a generative model, which describes how data is generated in terms of a probabilistic model. In simple words, it explains how data is generated visually.
Adversarial – The training of the model is done in an adversarial setting.
Networks – use deep neural networks for training purposes.

GAN has two components which has their respective functions:-
1) Discriminator – It is a supervised approach means It is a simple classifier that predicts data is fake or real. It is trained on real data and provides feedback to a generator.
2) Generator – It is an unsupervised learning approach. It will generate data that is fake data based on original(real) data. It is also a neural network that has hidden layers, activation, loss function. Its aim is to generate the fake image based on feedback and make the discriminator fool that it cannot predict a fake image. And when the discriminator is made a fool by the generator, the training stops and we can say that a generalized GAN model is created.
