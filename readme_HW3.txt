Problem Description : - 

In this homework one will practice building a multi-class image classification pipeline to classify daily life images (CIFAR10), based on the modern neural networks. Please keep the batch size untouched. The goals of this homework are as follows:

• understand how to use Pytorch to build multi-class classifiers.
• understand the mechanism of convolution in image classification.
• learn the power of non-linearity in modern neural networks.
• implement and apply a fully-connected multi-class image classifier.
• implement and apply a Convolutional Neural Networks (CNN) classifier.


In this homework, you are asked to implement fully-connected (MLP) and Convolutional Neural Networks (CNN) image classifier on CIFAR10 dataset. (A third model is trained as well) 


Data : - 

In these tests, we incorporate CIFAR10 dataset using a provided skeleton code. 


We use CIFAR10 classification dataset. Pytorch/torchvision has provide a useful dataloader to automatically download and load the data into batches. Data loader is provided in skeleton code.

How to Run : -

The respective logistics regressions and support vector machine is implemented using PyTorch

1. Skeleton Python code has been provided for updating (OPTIONAL)
2. Edit respective code in a text editor (Sublime Text was used to edit python code)
3. Using Google Colab, all associated libraries and packages were imported
*******
MODELS IN PYTHON CODE HAVE ALREADY BEEN ADDED TO NOTEBOOK FILE. SIMPLY FOLLOW THE BELOW INSTRUCTIONS UNLESS EDITING OF INITIAL CODE IS REQUIRED

4. Change only the section labeled 'Modified Section' in bold italics. Here, one will simply uncomment the model they wish to use, whilst keeping the other two models commented. MLP, CNN and a neural network without non-linear activation function (model) are provided in this section. 



Results/Conclusions :- 
1) CNN proved to be the most accurate model.
2) MLP proved to be the second most accurate model.
3) NN w/out non-linear activation function model proved to be the most time consuming and the least accurate model to train. 