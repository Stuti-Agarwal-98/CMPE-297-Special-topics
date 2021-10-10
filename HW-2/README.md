# Source
## Below are the reference links

## Keras Perceiver: https://keras.io/examples/vision/perceiver_image_classification/
## Perceiver IO Example: https://github.com/2796gaurav/code_examples/blob/main/Perceiver/Perceiver_optical_flow.ipynb
## Part a
### This is an implementation of Perciever using Keras.
### The cifar100 dataset was used with the Keras model.
### Inital data preperation is done to split train and test data. 
### data augmentations - normalize, resizing, flipping and zooming. 
### A feed forward network (FFN) used by the cross-attention module and transformer module.
### Patch implementation as well to extract data from the images we pass to the perceiver model.
### Finally the perceiver model aggregates the modules and patches in addition to a couple layers and is executed.
### The accuracy starts of similar to the authors execution output (5%, authors had 3%). However due to limited resources we stopped after the first epoch.

## Part b
### Using perceiver io for optical flow

## Demo
### Colabs have the results and visualisations
