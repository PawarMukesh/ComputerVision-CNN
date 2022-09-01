# Computer-Vision-Basic-CNN
## The file Is Contain Convolutional Neural Network Practical Implimentation With Inbuild DataSet Of Keras.

##  Working With CNN:
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


### How Convolutional Neural Network Works?
* Suppose, If we have image then we are apply filter over the image and extract all important feature and create a third function.
* Filter is apply on over the image and stride of filter is one, then multiply the Image pixel value with filter value, then the filter is move or jump to the next scan to extract the feature.

![image](https://user-images.githubusercontent.com/101791322/187871425-4f5388ee-f11e-462e-baf8-0aa68c776da5.png)

### What is padding?
* Padding is a process of adding cushion on original image, cushion means addition of rows and column both side on images.

#### There are two types of padding:

1.	Zero padding: Zero padding refers to the process of symmetrically adding zeros to the metrix.
2.	Adjusent padding: In this padding we are take the closet number.

![image](https://user-images.githubusercontent.com/101791322/187872401-36a82f3c-d857-47ed-bb20-7fecb1b5c7ca.png)

### Why Padding is used? 
* Padding is used to prevent loss of information and shrinkage of images. When padding is applied the formula is (n+2p-f+1)/s
Ex. 6+2-3+1/1 = 6 means the input size and output size becomes equal.

### Relu:
* Relu stand for rectified linear unit, for a non linear operation, the output is F(x) = max(0,x)

### Pooling Layer:
* This is a feature selection stage in CNN, Pooling layer extract the important information of third function that we are created There are three type of pooling layer:
1.	Max pool: Max pool layer extract the maximum information.
2.	Min pool: Min pool layer extract the minimum information.
3.	Mean/Average pool: Mean pool extract the average information.
In Max pooling the size of filter is 2*2 and the stride is also 2.

![image](https://user-images.githubusercontent.com/101791322/187920984-6a8a3bbe-c083-4ece-976d-2a94d5a1f6ef.png)

### Flatten Layer:
* Flatten layer is used to convert a any size/shape matrix into 1D array.

![image](https://user-images.githubusercontent.com/101791322/187921109-51728611-0723-4122-aa3d-9ecdd4754ca4.png)


### FCNN : 
* FCNN stand for fully connected neural network, in this stage each and every neuron is fully connected to each other.

![image](https://user-images.githubusercontent.com/101791322/187921277-d48e6075-97ab-4b9c-ab82-002004e929d7.png)

### Architecture of CNN:

![image](https://user-images.githubusercontent.com/101791322/187922137-478c4ed9-3891-49f3-ba63-4a95642c6804.png)













