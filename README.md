# Dashtoon Assignment
# Neural Style Transfer with VGG19

## Overview

This repository contains code for neural style transfer using the VGG19 model. The model takes a content image and a style image as input, producing a stylized output that combines the content of the former with the artistic style of the latter.

## Getting Started

### Prerequisites

- Python 3.x
- PyTorch
- torchvision
- PIL
- matplotlib
- numpy

Install the required dependencies using:

```bash
pip install -r requirements.txt
```
### Usage

Clone the repository
```bash
git clone https://github.com/SachdevaVansh/Dashtoon_assignment.git
```
### Navigate the project directory
```bash
cd Dashtoon_assignment
```
#### I have uploaded the sample images here in the Repository, one may upload his/her image and then copy the path of that image into the code 

### Model Details
The style transfer model is based on the VGG19 architecture pretrained on ImageNet. The code includes functions to load images, define feature extraction, calculate gram matrices, and perform style transfer using the Adam optimizer.

### Customization
You can customize the style transfer by modifying parameters such as content weight, style weight, and the layers used for feature extraction. Experiment with different content and style images for diverse artistic effects.

### Results
The stylized output will be saved or displayed at specified intervals during the training process. Adjust the script to save the final stylized image according to your preferences.

### Acknowledgments
This code is based on the neural style transfer algorithm popularized by Gatys et al. (2016) and utilizes the VGG19 model pretrained on ImageNet.


