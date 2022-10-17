# Face-Verification-and-Recognition


Many of the ideas presented here are from [FaceNet](https://arxiv.org/pdf/1503.03832.pdf).

Building a face verification and recognition system using FaceNet pre-trained model.

The network architecture follows the Inception model from [Szegedy *et al*..](https://arxiv.org/abs/1409.4842) 

**Face Verification** a 1:1 matching problem.

**Face Recognition** a 1:K matching problem.

FaceNet learns a neural network that encodes a face image into a vector of 128 numbers. By comparing two such vectors, you can then determine if two pictures are of the same person.

* Implementing one-shot learning to solve a face recognition problem

* Applying the triplet loss function to learn a network's parameters in the context of face recognition

* Mapping face images into 128-dimensional encodings using a pretrained model

* Performing face verification and face recognition with these encodings
