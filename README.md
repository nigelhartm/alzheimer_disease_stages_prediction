# Alzheimer disease type prediction - Bioimaging project
This project was done by [jeongahblairlee](https://github.com/jeongahblairlee) and [nigelhartm](https://github.com/nigelhartm) for the module Bioimage Analysis and Extended Phenotyping (Msc. Bioinformatics) in one week. As a dataset we used https://www.kaggle.com/datasets/sachinkumar413/alzheimer-mri-dataset. From there we tried to improve the prediction and implemented a SVM approach as well. Our main focus was in trying to understand the underlaying approaches/data needed to do a prediction of Alzheimer's disease types (Mild Demented, Moderate Demented, Non Demented, Very Mild Demented) based on brain MRI pictures. Fruther description and the presentation about our results.

# Further description and usage
We used Google colab to run our training and prediction, thats where our main.ipynb is coming from.
Our best result we achieved by using a SVM, which we saved as a pre-trained model and provide here as well (SOON).
This provided us an accuracy of 0.9825 in predicting the correct stage of Alzheimer's disease.

# Presentation
## Introduction
![alt text](https://github.com/nigelhartm/alzheimer_disease_stages_prediction/blob/main/presentation/01.jpg)
![alt text](https://github.com/nigelhartm/alzheimer_disease_stages_prediction/blob/main/presentation/02.jpg)
![alt text](https://github.com/nigelhartm/alzheimer_disease_stages_prediction/blob/main/presentation/03.jpg)
## Dataset
![alt text](https://github.com/nigelhartm/alzheimer_disease_stages_prediction/blob/main/presentation/04.jpg)
![alt text](https://github.com/nigelhartm/alzheimer_disease_stages_prediction/blob/main/presentation/05.jpg)
## Convolutional Neural Network
![alt text](https://github.com/nigelhartm/alzheimer_disease_stages_prediction/blob/main/presentation/06.jpg)
![alt text](https://github.com/nigelhartm/alzheimer_disease_stages_prediction/blob/main/presentation/07.jpg)
## SVM (Support Vector Machine)
![alt text](https://github.com/nigelhartm/alzheimer_disease_stages_prediction/blob/main/presentation/08.jpg)
## Further improvements (Data augmentation)
This we already tried at the CNN approach but didn't get good results. It is planned to do it on the SVM approach.
![alt text](https://github.com/nigelhartm/alzheimer_disease_stages_prediction/blob/main/presentation/09.jpg)

# Planned
* optimzing model (open)
* create webpage for project (done) -> http://nigelhartm.github.io/alzheimer_disease_stages_prediction
* implement a webpage with tensorflow for javascript (open)

# References
https://adni.loni.usc.edu/

https://www.alzheimers.net/

https://www.kaggle.com/datasets/jboysen/mri-and-alzheimers

https://ieeexplore.ieee.org/document/9521165

https://catalog.data.gov/dataset/alzheimers-disease-and-healthy-aging-data

https://www.nature.com/articles/s41598-020-79243-9

https://cordis.europa.eu/article/id/429468-the-final-epad-dataset-is-now-available-on-the-alzheimer-s-disease-workbench

https://www.kaggle.com/code/psycon/brain-mri-image-alzheimer-classifier/notebook

https://colab.research.google.com/github/ShanmukhVegi/Image-Classification/blob/main/Shanmukh_Classification.ipynb#scrollTo=JSapSw-h5HK0
