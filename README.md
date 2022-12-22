# Expanding Cross-Architectural Self-supervision for Multi-modal learning
This Repository contains the implementation of Final Project DL.


## Overview
Memes have become an online phenomenon and have grown in circulation with increased accessibility to the internet and editorial applications. This floods the internet with many memes and makes direct human supervision impossible. A plausible solution is to use AI to determine whether the memes are harmful. But sometimes, these memes subtly combine visual and textual cues to point to hate speech. Traditional deep learning architectures and techniques rely on uni-modality i.e., they only focus on images or textual data. But as mentioned earlier, sometimes memes use a combination of textual and visual cues for hate speech; this calls for deep learning techniques to be multimodal in their approach. Furthermore, human intelligence also relies on multiple modalities. Another bottleneck is in the form of the availability of annotations. As supervised techniques rely on input-label pairs to learn meaningful representations, scaling them is arduous and expensive. This is where we could depend on self-supervised learning to understand representations label-freely. So taking the above problem as the inception point, in this report, we have implemented two unimodal and two multimodal self-supervised approaches. In addition, we extend the implementation of CASS to multiple modalities and suggest a novel multimodal self-supervised technique CASS-MM (CASS-Multi-modal).




## Methodolgies Explored

- CLIP <https://arxiv.org/pdf/2103.00020.pdf>
### Model Structure
- DINO <https://arxiv.org/pdf/2104.14294.pdf>
### Model Structure
- CASS <https://arxiv.org/pdf/2206.04170.pdf>
### Model Structure


### Results
| Architecture | N | Bi | Dropout | Acc(%) |
| :---:         |     :---:      |          :---: |    :---:      |     :---:     |
| 1  |  4     |   [2,1,1,1]    | -   |  94.17%   |
| 2  |  3     | [3,3,3]      | 0.2 (Conv layers + hidden layer)  |  94.33%    | 


### Experimentation
A snapshot of experiments carried out. Detailed information can be found below:
<img src="Experiments/ExperimentImage1.jpeg" alt="Alt text" title="Optional title">
Please find the below link for the experimentations done during this project.


# Respository Details
The BestArchitecture folder contains the model code used to setup and train the architecture along with the necessary plots. Each Model folder contains the following details
- Python Notebook having the results and plots for each model configuration
- main.py file , which has to used to execute the model
- resnetModel.py file, which defines the base architecture of the modified ResNet model
- PlotConfusionMatrix.py file for the plotting the confusion matrix , Train vs Validation plots
- Confusion_Matrix folder for storing the necessary variable created during the straining and using it for plotting graphs
- checkpoint folder stored the best model obtained during the traininf
- plots contains the plot generated for the model specified
- Experiments folder contains the other implemenations, we tried out, like Early Stopping  , changing channels etc.
### Code References: 
https://github.com/kuangliu/pytorch-cifar

