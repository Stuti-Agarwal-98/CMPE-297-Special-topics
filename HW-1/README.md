# HW 1
 ## Objective: Implement contrastive representation learning with SimCLR on small dataset.

## Built with:

### Pytorch (1)
### Tensorflow (2)

## Source:
# Pytorch : https://medium.com/analytics-vidhya/understanding-simclr-a-simple-framework-for-contrastive-learning-of-visual-representations-d544a9003f3c
# Tensorflow : https://github.com/sayakpaul/SimCLR-in-TensorFlow-2
## PART A:
### This is an implementation using Pytorch. I use the milli_imagenet dataset, a custom small version with 1250 training and 250 test records. The pretrained model used is a resnet18 model with a couplpe linear layers and relu functions. A couple of image augmentations are done such as color distortion and normalization. Then the training proceeds for the (model + simclr). 

## PART B:
### This is an implementation using Tensorflow. This used a subset of the ImageNet dataset, 1250 training and 250 testing. This had the same augmentations applied as we did in PyTorch. And the pretrained model was identical as well. Different linearities and projections were used and we were eventually able to get a 34% accuracy.
