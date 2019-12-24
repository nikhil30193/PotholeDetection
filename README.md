# PotholeDetection
A CNN model on pothole prediction.

Data is taken from kaggle which is a folder of images with potholes and normal roads. Link of dataset is given below. Dataset - https://www.kaggle.com/atulyakumar98/pothole-detection-dataset

This dataset have some currupted images, so deleted those corrupt images and resize images and the link of resized images is given below.

resized images - https://drive.google.com/open?id=1ZQTHiHMgANtKLyYtWgFg12kRlirRxP9i

From these image files first I create a csv file of pixels of images and label them 1 and 0 for potholes and normal respectively. I use  Jupyter Notebook for creating csv.Link of csv fie is given below.

Csv file - https://drive.google.com/open?id=1bfHhHfwKSQ4ItIBsJrcO_CsB0A8WSSDv

From this csv file I create a CNN model and the accuracy of 88.7%. And I use Google Colab for model building.
