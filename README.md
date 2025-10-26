# cnn-vgg6-config-assignment
This assignment focuses on exploring VGG6 on CIFAR-10 with different configurations
 and analyzing model performance based on these configurations.

I have prepared CIFAR10 data with normalization using standard RGB channels mean and standard deviation of CIFAR10 images
I have used RandomCrop and RandomHorizontalFlip for data transformation. 
RandomCrop – Crops a random 32*32 region from a padded image 
RadomHorizontalFlip – Left/Right mirroring of the image
I also have AutoAugment and random erasing in the code


This code can be run by clicking on google colab link provided in python notebook. 
 
With the change in activation function, optimizer, batch size, learning rate and epochs, the accuracy varied.

I found from my wanddb plots that the following configuration gave best accuracy 
Activation function: Relu
Optimizer :  lbfgs
Batch size :  64
Epochs: 40
Learning rate : 0.1
Got val/accuract of 0.8986 with these configurations


