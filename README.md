## Project Overview

The goal of the project is to classify images of dogs according to their breed. This project accepts any user-supplied image as input. If a dog is detected in the image, it will provide an estimate of the dog's breed. If a human is detected, it will provide an estimate of the dog breed that is most resembling. 

## Project Content

Step 0: Import Datasets

Step 1: Detect Humans

Step 2: Detect Dogs

Step 3: Create a CNN to Classify Dog Breeds

Step 4: Use a CNN to Classify Dog Breeds

Step 5: Create a CNN to Classify Dog Breeds

Step 6: Algorithm to determine Dog Breed

Step 7: Testing the Algorithm

## Library

sklearn, keras, numpy, glob, random, cv2, matplotlib.pyplot, tqdm, PIL, extract_bottleneck_features

## File & folder structure

dog_app.ipynb - Jupyter notebook containing code for this project

Test folder - contains input image file for test the algorithm

saved_models - necessary models are saved in this folder

bottleneck_features - related bottleneck features are available in this folder

haarcascades- Xml file for OpenCv face detector class.

## Test Result

The output is accurate for the given test cases. Most of the cases it identified right breed and also find the resemblence of the dog breed from even blur human image. For example French Bulldog and Boston Terrier are very similar breed which was correctly identified by the algorithm but failed to identify between Whippet and Italian Greyhound.

## Points of improvement

It looks like time-consuming and requires high computational power.
Model needs to find the correct breed for look-alike dog breeds. 
It should better in finding the resemblance of dog breed from human image.

## Conclusion

I have selected Inception bottleneck features over VGG-19 gives better accuracy of 80%. Inception is sutiable model because of its efficient for the high-performance output. Ability to extract features from input data at varying scales through the utilisation of varying convolutional filter sizes. 

## Blog

The detail of this project can be found at the blog available [here](https://medium.com/@prabhagtec/dog-breed-classifier-13a81a614cb3)

## Acknowledgements

credits to Udacity’s Data Scientist Nanodegree Program

