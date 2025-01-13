# Melanoma Detection
In this assignment I will build a CNN based model which can accurately detect melanoma. Melanoma is a type of cancer that can be deadly if not detected early. It accounts for 75% of skin cancer deaths. A solution that can evaluate images and alert dermatologists about the presence of melanoma has the potential to reduce a lot of manual effort needed in diagnosis.


## Table of Contents
* [General Info](#general-information)
* [Technologies Used](#technologies-used)
* [Conclusions](#conclusions)
* [Acknowledgements](#acknowledgements)

## General Information
This project will help to detect Melanoma early so that appropriate action can be taken by the community.

The dataset consists of 2357 images of malignant and benign oncological diseases, which were formed from the International Skin Imaging Collaboration (ISIC). All images were sorted according to the classification taken with ISIC, and all subsets were divided into the same number of images, with the exception of melanomas and moles, whose images are slightly dominant.

The data set contains the following diseases:
	- Actinic keratosis
	- Basal cell carcinoma
	- Dermatofibroma
	- Melanoma
	- Nevus
	- Pigmented benign keratosis
	- Seborrheic keratosis
	- Squamous cell carcinoma
	- Vascular lesion

## Conclusions
- It's clearly visible that accuracy has been improved & there is no signs of overfitting or underfitting of the learning algorithm using Augmentor library 
- Dropout helped learning algorithm to improve on accuracy
- The implementation of class rebalancing using Augmentor library has enhanced the model's performance across both training and validation datasets
- Finally the model has 75% training and 76% validating accuracy

## Technologies Used
- TensorFlow - version 2.17.1
- Python - version 3.10
- pandas - version 2.2.2
- matplotlib - version 3.7.0
- plotly - version 5.23.0
- numpy - version 1.23.5

## Acknowledgements
- TensorFlow, Pandas, Matplotlib, Plotly, Numpy offical documentation & Stackoverflow

## Contact
Created by [@sahilavasthi] - feel free to contact!
