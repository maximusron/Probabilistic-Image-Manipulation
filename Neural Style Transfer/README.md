## Neural Style Transfer on a RESNET-50 architecture

### Abstract

This project attempts Neural Style Transfer with the new constraint of sticking to ResNet Architecture.

This work entails a mini research project on aiming to replicate the widely accepted NST performance by commonly used models like VGG or TensorFlow's NST model.

ResNet is not inherently optimal for NST as its capture of feature is not as robust as other architectures

<!-- ![Robustness Graph](<./Results/imageedit_0_4557857959.jpg>) -->

<img src="https://github.com/maximusron/Probabilistic-Image-Manipulation/blob/main/Neural%20Style%20Transfer/robustness_graph.jpeg?raw=true" width=60% height=60%>
 
This can be illustrated be preliminary performance using ResNet50 for NST with standard loss parameters.

I have analyzed different layers of ResNet architecture to find the optimal content and style layers for NST as well as implemented the content and style losses for NST.

The main challenge was to obtain a robust feature transfer as ResNet is not by default an optimal choice of model for NST as its feature capture is not as robust as other nets.



Results with trials can be viewed in NST__trials.pptx in this repo
