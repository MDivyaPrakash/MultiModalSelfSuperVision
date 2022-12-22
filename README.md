# Understanding multi-modal self-supervision and out of distribution performance
This Repository contains the experiments and implementation of Deep Learning Final Project

## Abstract
In the work shown in this report, we try to maximize the test accuracy of the ResNet18 model by keeping a constraint where the number of trainable parameters of the new ResNet18 architecture should not exceed 5 million. We experiment on the ResNet18 model by modifying its layer structure and subjecting it to various parameters and optimizers. Finally, inferring from the experimental results, we propose  modified architectures of ResNet18, which exhibits the highest test accuracy,  given the parameter constraint. The dataset which was used was the CIFAR-10 image classification datase.

### Code References: 
https://github.com/kuangliu/pytorch-cifar
