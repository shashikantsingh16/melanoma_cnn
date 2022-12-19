# Project Name
> melanoma-detection-assignment using CNN

## Table of Contents
* [General Info](# Convolutional Neural Network (CNN) is a model which is trained to identify melanoma (a type of skin cancer) by feeding image of the skin lesion
* [Technologies Used](# Python, Pandas, Matplotlib, Keras API, Tenserflow )
* [Conclusions](# The neural network model is working good for 9 class classification problem for which we have created)
* [Acknowledgements](# stackoverflow)


## General Information
CNN Model is used to classify any specifc given input into one of the 9 ctegories of the melanoma images which are closeup shot for the skin from the different patients.
This model tries to detect the early signs from the categorized images and check if it is fatel or not and it helps medical practioner to save time to identify the lesion if it belongs to melanoma or not.


## Conclusions
- The model is having a accuracy of 95% on train data and 83% on validation data set.
- We used 50 epochs to train data with batch size 32. However the optimum results were reached in about 14 epochs and we could have used an early stopping.
- Loss function used is SparseCategoricalCrossentropy, Optimizer is adam and accuracy was used as metric
- seborrheic keratosis class has the least number of samples
- melanoma, pigmented benign keratosis and basal cell carcinoma classes dominate the data in terms proportionate number of samples


## Technologies Used
- Python - version 3.0
- Google Collab
- Visual Studio Code
- Keras API and Tenserflow
- Matplotlib for visualization


## Contact
Created by [@shashikantsingh16] - connect with me for more info
