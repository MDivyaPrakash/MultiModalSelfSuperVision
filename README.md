# Understanding multi-modal self-supervision and out of distribution performance
This Repository contains the experiments and implementation of Deep Learning Final Project

## Abstract
Memes have become an online phenomenon and have grown in circulation with increased accessibility to the internet and editorial applications. This floods the internet with many memes and makes direct human supervision impossible. A plausible solution is to use AI to determine whether the memes are harmful. But sometimes, these memes subtly combine visual and textual cues to point to hate speech. Traditional deep learning architectures and techniques rely on unimodality i.e.; they only focus on images or textual data. But as mentioned earlier, sometimes memes use a combination of textual and visual cues for hate speech; this calls for deep learning techniques to be multi-modal in their approach. Furthermore, human intelligence also relies on multiple modalities. Another bottleneck is in the form of the availability of annotations. As supervised techniques rely on input-label pairs to learn meaningful representations, scaling them is arduous and expensive. This is where we could depend on self-supervised learning to understand representations label freely. 

So taking the above problem as the inception point, in this work, we have implemented two unimodal and two multimodal self-supervised approaches. In addition, we extend the implementation of CASS to multiple modalities.

### Code References: 
https://github.com/kuangliu/pytorch-cifar
