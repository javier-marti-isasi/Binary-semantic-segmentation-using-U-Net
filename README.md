# Binary semantic segmentation using U-Net

Binary semantic segmentation using U-Net in TensorFlow 2 / Keras. 


## Directory Structure

**All the code files and folders follow the following structure in ipynb file.**

```
├── training.tif
├── testing.tif
├── training_groundtruth.tif
├── testing_groundtruth.tif
├── patches
│   ├── images
│   └── masks
└── model.hdf5
```

## Introduction

The line of research is motivated by the need to accurately segment mitochondria from images. To solve this problem, we will use binary semantic segmentation using U-Net in TensorFlow 2 / Keras.

It is used U-Net model, which is trained on <a href="https://www.epfl.ch/labs/cvlab/data/data-em/" target="_blank">this dataset</a>. It is annotated mitochondria in two sub-volumes. Each sub-volume consists of 165 slices in 1024x768. 

U-Net is a semantic segmentation technique originally proposed for medical imaging segmentation. U-Net was introduced in the paper, <a href="https://arxiv.org/abs/1505.04597" target="_blank">U-Net: Convolutional Networks for Biomedical Image Segmentation</a>. The model architecture is fairly simple: an encoder (for downsampling) and a decoder (for upsampling) with skip connections.


## Instructions

Please, follow the instruction in the provided notebook.


## Predicted segmentation examples:

![descarga](https://user-images.githubusercontent.com/73080100/184480812-103a7193-c33c-4355-8d5b-b666cb8214d1.png)
![descarga (1)](https://user-images.githubusercontent.com/73080100/184480818-83cb044d-7abf-41c1-a7b9-1289f862a97e.png)
![descarga (2)](https://user-images.githubusercontent.com/73080100/184480815-3f35843d-2f7f-4eb9-8970-72ae6fd340e6.png)



