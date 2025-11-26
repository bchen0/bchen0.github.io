---
title: "Low-Rank Tensor-Network Encodings for Video-to-Action Behavioral Cloning"
collection: publications
venue: 'Transactions on Machine Learning Research (TMLR)'
---
We describe a tensor-network latent-space encoding approach for increasing the 
scalability of behavioral cloning of a video game player’s actions entirely 
from video streams of the gameplay. Specifically, we address challenges 
associated with the high computational requirements of traditional 
deep-learning based encoders such as variational autoencoders that prohibit 
their use in widely available hardware or for large scale data. Our approach 
uses tensor networks instead of deep variational autoencoders for this purpose, 
and it yields significant speedups with no loss of accuracy. Empirical results 
on ATARI games demonstrate that our approach leads to a speedup in the time it 
takes to encode data and train a predictor using the encodings (between 2.6× to 
9.6× compared to autoencoders or variational autoencoders). Furthermore, the 
tensor train encoding can be efficiently trained on CPU as well, which leads to 
comparable or better training times than the autoencoder and variational 
autoencoder trained on GPU (0.9× to 5.4× faster). These results suggest 
significant possibilities in mitigating the need for cost and time-intensive 
hardware for training deep-learning architectures for behavioral cloning.
[<a href="https://openreview.net/forum?id=w4DXLzBPPw">Paper</a>]
