# cnn-melonama-cancer
# Author: @Prem Kumar Subudhi
#9-April-2024
# Verson 1

To build a CNN based model which can accurately detect melanoma.

# Project Name
SkinCancer Melonama Detection.
	
Build a multiclass classification model using a custom convolutional neural network in TensorFlow

## Table of Contents
* [General Info](#general-information)
* [Technologies Used](#technologies-used)
* [Conclusions](#conclusions)
* [Acknowledgements](#acknowledgements)

<!-- You can include any other section that is pertinent to your problem -->

## General Information
Problem Statement:

To build a CNN based model which can accurately detect melanoma. Melanoma is a type of cancer that can be deadly if not detected early. It accounts for 75% of skin cancer deaths. A solution that can evaluate images and alert dermatologists about the presence of melanoma has the potential to reduce a lot of manual effort needed in diagnosis.

- Provide general information about your project here.
	<> This project will predict the cancer cell using model trained with 9 different classes form the given dataset. The dataset consists of 2357 images of malignant and benign oncological diseases, which were formed from the International Skin Imaging Collaboration (ISIC). The diseases are mentioned elow.
		Actinic keratosis
		Basal cell carcinoma
		Dermatofibroma
		Melanoma
		Nevus
		Pigmented benign keratosis
		Seborrheic keratosis
		Squamous cell carcinoma
		Vascular lesion

- What is the background of your project?
	<> The goal of the study is to create a bespoke convolutional neural network (CNN) model that can reliably identify the lethal cancer type melanoma. The International Skin Imaging Collaboration (ISIC) provided 2357 images of benign and malignant oncological disorders, which make up the dataset. Data reading, dataset construction, model building and training, data augmentation, managing class imbalances, and model performance evaluation are all processes in the project pipeline. By automating the melanoma diagnosis process via image analysis, the goal is to decrease the amount of manual labor required for the first detection.
- What is the business probem that your project is trying to solve?
	<> "We aim to develop a CNN model that can accurately diagnose the type of skin cancer in any patient, based on a given or unseen image, without requiring human intervention. The model should be able to provide a prediction within minutes or even a few seconds."

	This version emphasizes the goal of developing a CNN model for skin cancer diagnosis, and clarifies that the model should be able to provide a quick and accurate prediction based on an image, without requiring human input.

- What is the dataset that is being used?
	SkinCancer_ISIC_Dataset :Skin Imaging Collaboration (ISIC) provided 2357 images of benign and malignant oncological disorders, which make up the dataset.  
	Dataset used https://drive.google.com/file/d/1xLfSQUGDl8ezNNbUkpuHOYvSpTyxVhCs/view?usp=sharing
<!-- You don't have to answer all the questions - just the ones relevant to your project. -->

## Conclusions.

The Model acuracy:

	Epoch 20: val_accuracy improved from 0.81189 to 0.84615, saving model to my_model1.keras
	179/179 ━━━━━━━━━━━━━━━━━━━━ 98s 547ms/step - accuracy: 0.8630 - loss: 0.3811 - val_accuracy: 0.8462 - val_loss: 0.5555
	
	Epoch 30/30
	179/179 ━━━━━━━━━━━━━━━━━━━━ 102s 572ms/step - accuracy: 0.9149 - loss: 0.2247 - val_accuracy: 0.8573 - val_loss: 0.6268

	With more epoch the model is getting more overfitte

	Dataset Distribution:
	Class=0, n=114 (5.092%)
	Class=1, n=376 (16.793%)
	Class=2, n=95 (4.243%)
	Class=3, n=438 (19.562%)
	Class=4, n=357 (15.945%)
	Class=5, n=462 (20.634%)
	Class=6, n=77 (3.439%)
	Class=7, n=181 (8.084%)
	Class=8, n=139 (6.208%)

Test Result: Model Prediction done using Test folder of the above dataset. 

	1/1 ━━━━━━━━━━━━━━━━━━━━ 0s 431ms/step
	Actual Class basal cell carcinoma
	Predictive Class squamous cell carcinoma

<!-- You don't have to answer all the questions - just the ones relevant to your project. -->


## Technologies Used
	Python 3 (ipykernel)
	Python version:  3.11.5 | packaged by Anaconda, Inc. | (main, Sep 11 2023, 13:26:23) [MSC v.1916 64 bit (AMD64)]
	TensorFlow version:  2.16.1
	System information: 
	Windows
	10
	('64bit', 'WindowsPE')
	<!-- As the libraries versions keep on changing, it is recommended to mention the version of library used in this project -->

## Acknowledgements
Give credit here.
- This project was inspired by...UPGRAD

- This project was based on [this tutorial](https://learn.upgrad.com/course/4705/segment/47956/289239/880085/4398556).


## Contact
Created by [@psubudhi] - feel free to contact me!


<!-- Optional -->
<!-- ## License -->
<!-- This project is open source and available under the [... License](). -->

<!-- You don't have to include all sections - just the one's relevant to your project -->
