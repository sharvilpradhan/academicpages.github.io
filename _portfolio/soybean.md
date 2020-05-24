---
title: "Leaf Wilting Identification in Soybean plants"
excerpt: "Detecting early signs of disease in Soybean plants by analyzing leaf images and predicting extent of wilting"
collection: portfolio
---



## Description
This project aims to discover early signs of disease in soybean plants on the basis of images of soybean leaves. The input data conists of labelled as well as unlabelled data of soybean leaf images. We collaborated with the Agricultural Deptarment of NC State who provided the data containing the images.

## Objective
The purpose of this project is to identify and classify images into one of the 5 categories based on the extent of wilting in soybean leaves.


## Advantage

I have implemented semi-supervised learning where I am using unlabelled data initially to extract important data from it and adding that to one of the 5 categories (labels). This helps in including important features that might help in the classification task and it also helps to discard images that are bad or that do not belong to any of the 5 classes.
Transfer learning using a pre-trained VGG-16 model is carried out to classify the soybean images. 

This was a competition project in association with the Agricultural Department at NC State University. Our group had the best classification accuracy of 82%
