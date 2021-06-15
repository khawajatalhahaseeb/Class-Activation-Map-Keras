# Class-Activation-Map-Keras
Class Activation Map (CAM) is a powerful technique used in 'Computer Vision' to visualize and get insights from a Convolutional Neural Network (CNN). It is used by scientists to inspect the image to be categorized and it also helps to understand which parts of that image have contributed more to the final output of the model. It creates a heatmap of 'Class Activation' over the given input image. It tells which features the model is looking for.

In this example, I am using Keras to implement CAM because Keras is easy to use and it also saves a lot of time. I will be using a pre-trained CNN, VGG16 model, using weights deriving from its training on the Imagenet dataset.

### Input Image:
![sheep](https://user-images.githubusercontent.com/85954399/122110069-8d0e9b80-ce37-11eb-9190-876a42c9e741.png)

### Class Activation Map:
![output_sheep](https://user-images.githubusercontent.com/85954399/122110118-9d267b00-ce37-11eb-9652-81893acb455e.jpeg)

### Reference
- https://arxiv.org/abs/1409.1556
- https://keras.io/api/applications/vgg/#vgg16-function
- https://en.wikipedia.org/wiki/ImageNet
- http://cnnlocalization.csail.mit.edu/Zhou_Learning_Deep_Features_CVPR_2016_paper.pdf
