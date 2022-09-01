# Computer-Vision-Basic-CNN
## The file Is Contain Convolutional Neural Network Practical Implimentation With Inbuild DataSet Of Keras.

# Working With CNN:
## Introduction Of CNN
### •	A Convolutional neural network (CNN or ConvNet) is a class of artificial neural network.
### •	In Neural Network one of the main category to do image classification, object detection and segmentation etc.. are some of the areas where  CNN are widely used.

## Before understand Convolutional neural network first take the look of image.

### What is meant by Image?
* Image is a collection of pixel as well as 2D representation of real word object is called as image.

### Types Of Image

### There are two type Of Images.
#### 1.	Gray Scale Image: 

![image](https://user-images.githubusercontent.com/101791322/187868729-2c2dfd64-c078-43c3-b9f9-51b733f8590b.png)


*	In Gray scale image only one channel is present
* The range of pixel in gray scale image is 0 to 255. where 0 represent to black and 255 represent to white.

#### 2.	RGB Scale Image:

![image](https://user-images.githubusercontent.com/101791322/187868219-3eedb3db-944f-4726-93f7-bf555db5a98f.png)

 
* In RGB Image three channel is present red, green and blue.
* The range of pixel in RGB image is 0 to 255, where 0 represent the black and 255 represent the red, green and blue.

### How Image has been form:
* Pixel  Edges  Pattern  Parts of object  Object  Image.

![image](https://user-images.githubusercontent.com/101791322/187869411-3fb59ca7-0e2b-4c2e-9e42-314bb03c37d0.png)

####  Now lets understand what is convolution?

* Convolution is a mathematical operation where two function are convoluted to produce third function is called as convolution. Let’s understand the some terms used to create third function:

* Filter: Filter is also known as kernel it is used to extract the features from the images.

* Stride: Stride is a movement and jump of the filter over the image. 

### Types of filters:
There are different types of filters are used in convolutional neural network.
*	Sobel filter: The sobel filter is used to edge detection.
*	Box filter: Box filter is a low pass filter that’s smooths the images by making each output pixel the average of surrounding ones remove noise and edges from the images.
*	Gaussian filter: A gaussian filter is also known as line filter, it is usually used to blur the image and remove the noise from image.





