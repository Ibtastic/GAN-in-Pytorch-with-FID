# GAN-in-Pytorch-with-FID

The main idea behind this repo is to implement DCGAN in Pytorch with some improvement techniques and implement Fretchet Inception Distance along with it. GANs are one of my favorite neural networks and one of the biggest pain points was assesing it's performance as precisely as we can do for other neural networks. Knowing when to stop the training(reaching Nash equilbirium) or comparing two GAN models was never straightforward. This drawback is overcomed by using Fretchet Inception Distance which is also considered superior to it's predecessor Inception Score.

FID was introduced in the paper [GANs Trained by a Two Time-Scale Update Rule Converge to a Local Nash Equilibrium](https://arxiv.org/abs/1706.08500)

I have picked up the underlying DCGAN implementation from this [Pytorch tutorial](https://pytorch.org/tutorials/beginner/dcgan_faces_tutorial.html) and have iteratively improved upon it by some hacks discussed in the notebook and compared performance between experiments using FID(for which I also provide a comprehensive explanation). 


