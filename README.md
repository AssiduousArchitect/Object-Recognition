# Obejct recognition

The onset of convolutional neural networks brought about a revolution in the way how a computer "understands" images. Computer vision is currently on the bleeding edge of A.I. research, and we have a lot yet to learn. 

In this detailed IPython Notebook, we will train a classifier to recognize whether the image contains one of the images we trained it to identify.

For this project, I will be using [Google Colab](https://render.githubusercontent.com/https://colab.research.google.com/). For those who are unaware, it is a research project created to disseminate ML education and you can train your neural networks on their Tesla K80 GPUs. It sure speeds up the entire training process. Do check it out.

## Table of contents:
1. Introduction.  
2. Prerequisites.  
3. How to run.

## 1. Introduction.
Object recognition is a computer vision technique for identifying objects in images or videos. Object recognition is a key output of deep learning and machine learning algorithms.

We will train our neural network on CIFAR-10 (Canadian Institute For Advanced Research) Dataset. This dataset contains 50,000 images which belong to 10 different classes. The following picture will give you a clear idea.

![Dataset Sample](http://parneetk.github.io/images/2017-01-23-cnn-cifar10_files/2017-01-23-cnn-cifar10_8_0.png)

Our neural network will learn how to differentiate between an aeroplane, an automobile, a bird, a cat, a deer, a dog, a frog, a horse, a ship, and a truck. We grown-ups can do this in a fraction of a second but computers are nowhere near to our visual prowess.  


## 2. Prerequisites.  
Make sure that you install the following libraries, if you are running it on yours system:
  + matplotlib
  + numpy
  + sklearn
  + pickle
  + os
  + keras
  + skimage
  + seaborn
  + pandas

## 3. How to run.

If you are interested in modifying this model and training it yourself, then please feel free to do so.    
i. Download the IPython Notebook.  
ii. Open [google Colaboratory.](https://colab.research.google.com/ "Colab time") / Run Jupyter notebook.  
iii. Upload this notebook from your system.  
iv. Download the [dataset](https://www.cs.toronto.edu/~kriz/cifar-10-python.tar.gz) and upload it into your GDrive.
v. Get creative and aim for better results.
