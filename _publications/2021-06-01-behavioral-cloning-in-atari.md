---
title: "Behavioral cloning in Atari games using a combined variational autoencoder and predictor model"
collection: publications
venue: 'IEEE CEC 2021 Session on Games'
---
We explore an approach to behavioral cloning in video games. We are motivated to pursue a learning architecture that is 
data efficient and provides opportunity for interpreting player strategies and replicating player actions in unseen 
situations. To this end, we have developed a generative model that learns latent features of a game that can be used 
for training an action predictor. Specifically, our architecture combines a Variational Autoencoder with a discriminator
mapping the latent space to action predictions (predictor). We compare our model performance to two different behavior 
cloning architectures: a discriminative model (a Convolutional Neural Network) mapping game states directly to actions, 
and a Variational Autoencoder with a predictor trained separately. Finally, we demonstrate how we can use the advantage 
of generative modeling to sample new states from the latent space of the Variational Autoencoder to analyze player 
actions and provide meaning to certain latent features.
[<a href="https://ieeexplore.ieee.org/document/9505001">Paper</a>]
[<a href="https://github.com/bchen0/vae_behavior_cloning">Code</a>]

Recommended citation: •	Brian Chen, Siddhant Tandon, David Gorsich, Alex Gorodetsky, and Shravan Veerapaneni.  Behavioral cloning in Atari games using a combined variational autoencoder and predictor model. In <i>IEEE CEC 2021 Session on Games</i>, 2021.
