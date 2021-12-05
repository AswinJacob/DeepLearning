FACE MASK DETECTION

Abstract

Post covid, many establishments are finding it hard to detect protocol violations, as the time and labour spent for the same incurrs high cost and is highly inefficient. The main aim of this project is to detect violations, like not wearing a mask in a workplace, and notify the officials. The projected is implemented in Python using Keras, Tensorflow and OpenCV. 

Project Overview

An image with a face is fed to a cascade classifier which identifies the Region of Interest (ROI) and give the coordinates of the detected face along with the height and width parameters. This is further resized to a 100x100 image and fed to the pre-trained CNN model, which will provide an output as 'With mask' or 'Without mask'.

Dataset

The dataset consisted of 1376 images, 690 face images with masks and 686 without masks. 
The original dataset is prepared by Prajna Bhandary and available at Github.

Data Preprocessing

The ROI image is converted to grayscale and then resized to 100x100. This is then reshaped to a 4D array input to be fed to the CNN model. 
2 categories are created as 'with mask' and 'without mask'.






