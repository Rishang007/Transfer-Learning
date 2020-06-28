# Transfer-Learning

## Problem Statement
In this project, we are classifying 15 different types of documents (images) using Convolutional Neural Network. 
This project uses the concept of transfer learning in which pretrained weights are used (trained on a large dataset) in different problems.  


## Models

On this data, we are training 3 different types of models. Each model is analyzed using tensorboard and due observation is provided of the analysis.
We are using VGG-16 architecture with ImageNet data pretrained weights

Model-1  

  <b>INPUT --> VGG-16 without Top layers(FC) --> Conv Layer --> Maxpool Layer --> 2 FC layers --> Output Layer</b>
 
Model-2  

  <b>INPUT --> VGG-16 without Top layers(FC) --> 2 Conv Layers identical to FC --> Output Layer</b>
    
Model-3  

  <b>INPUT --> VGG-16 without Top layers(FC) --> 2 Conv Layers identical to FC --> Output Layer</b>
