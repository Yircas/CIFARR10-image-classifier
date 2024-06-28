# CIFAR10-image-classifier
This is a PyTorch implementation of a simple image classification model for the CIFAR-10 dataset. It basically takes images of different objects and recognizes them as one of the following 10 classes:

![Example](https://production-media.paperswithcode.com/datasets/4fdf2b82-2bc3-4f97-ba51-400322b228b1.png "CIFAR-10 class examples")

## source
This follows a tutorial from [this blog post](https://medium.com/bitgrit-data-science-publication/building-an-image-classification-model-with-pytorch-from-scratch-f10452073212), credits go to the tutorial's author. <3

## Prerequisites
- I'd recommend Conda to setup this project. You can get Conda by installing [Anaconda/Miniconda](https://www.anaconda.com/download/success).
- You need [Jupyter](https://jupyter.org/) or a Code Editor like [VS Code](https://code.visualstudio.com/download) with the [Jupyter extension](https://marketplace.visualstudio.com/items?itemName=ms-toolsai.jupyter) to view .ipynb-files.
- Currently a GPU with [Cuda](https://developer.nvidia.com/cuda-downloads) is needed for training, make sure you have this

## Setup
1. Clone this repository with "git clone https://github.com/Yircas/CIFAR10-image-classifier.git"
2. Inside the cloned project, you run "conda env create -f environment.yml"
3. Activate your created environment with "conda activate cifar10-image-classifier"

## Use
All the important code is currently inside classifier.ipynb. You should run all cells in order to get the project working.