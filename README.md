Project_Two_Team4 by Tremayne T. Desalegn B. and Brandon D.

# Using Logistic Regression & Decision Tree Models for Diabetes Prediction using limited features.

<img width="917" alt="Screenshot 2024-06-11 at 4 34 23 PM" src="https://github.com/BrandonDavidson/Project_two-Team_Four/assets/159976118/db54d7d3-ccdc-462c-9d8d-7e2c53b94d33">


Our decision tree model was used to predict diabetes based on various health indicators. The dataset was preprocessed and the decision tree classifier was trained and evaluated. We visualized the model's performance using matplotlib.
Our logistic regression model was used to predict the presence of diabetes in individuals based on various health indicators.

## Table of Contents
- [Project Overview](#project-overview)
- [Dataset](#dataset)
- [Model Training and Evaluation](#model-training-and-evaluation)
- [Visualization](#visualization)
 
## Project Overview

The goal our project was to predict whether an individual has diabetes based on high blood pressure, general health, education, and income.
The project uses a decision tree classifier to make predictions and evaluates its performance using various metrics.
We used the decision tree to visualize and understand the decision-making process.
We also built a logistic regression model to predict the presence of diabetes in individuals based on High Blood Pressure, General Health, Education, and Income using a data set comprised of CDC data. 

## Dataset

The Behavioral Risk Factor Surveillance System (BRFSS) is a health-related telephone survey that is collected annually by the CDC. Every year the survey collects responses from over 400,000 Americans on health-related risk behaviors, chronic health conditions, and the use of preventative services. It has been conducted every year since 1984. For this project a CSV of the dataset was available on Kaggle for the year 2015 to be used. This original dataset contains responses from 441,455 individuals and has 330 features. These questions directly ask of participants, or calculated variables based on individual participant responses. We then found a data set inside of the same file that focuses on Diabetes lowering that 441,445 number of people that participated to 253,680. 

Our process that we took to clean up the data: 

<img width="1024" alt="Screenshot 2024-06-11 at 4 11 48 PM" src="https://github.com/BrandonDavidson/Project_two-Team_Four/assets/159976118/f1834a9b-f00c-4041-bd64-083d210284f3">
<img width="1022" alt="Screenshot 2024-06-11 at 4 14 37 PM" src="https://github.com/BrandonDavidson/Project_two-Team_Four/assets/159976118/1b85e229-268b-4b24-9855-60843ce28471">
<img width="1019" alt="Screenshot 2024-06-11 at 4 15 57 PM" src="https://github.com/BrandonDavidson/Project_two-Team_Four/assets/159976118/6e92b563-b1ef-4ef1-90c9-98ff70ceee6b">
<img width="1028" alt="Screenshot 2024-06-11 at 4 18 25 PM" src="https://github.com/BrandonDavidson/Project_two-Team_Four/assets/159976118/3bbe8711-8528-4606-bb1a-3e3a0125d4ba">
<img width="1018" alt="Screenshot 2024-06-11 at 4 19 41 PM" src="https://github.com/BrandonDavidson/Project_two-Team_Four/assets/159976118/cac9332b-8c67-4749-a36a-d7cd67a53ee5">
<img width="1018" alt="Screenshot 2024-06-11 at 4 19 41 PM" src="https://github.com/BrandonDavidson/Project_two-Team_Four/assets/159976118/886c141f-6af4-4e02-9475-8a6a68df8382">
<img width="1015" alt="Screenshot 2024-06-11 at 4 20 31 PM" src="https://github.com/BrandonDavidson/Project_two-Team_Four/assets/159976118/09f728b7-f50f-44b1-bf2e-531a4ddd541f">
<img width="1018" alt="Screenshot 2024-06-11 at 4 21 19 PM" src="https://github.com/BrandonDavidson/Project_two-Team_Four/assets/159976118/2a886a62-3876-488a-a692-f82d0ac68a47">

# Model Training and Evaluation

When training the model, we took steps to ensure that the variables used were sufficiently distinct from each other. This approach aimed to create clear, polar opposite features, helping the model to better identify false positives and avoid overly simplistic one-to-one conclusions. By ensuring that the input features provided opposing information, we aimed to improve the model's ability to generalize and accurately distinguish between different classes and enhancing its reliability.

Our process that we took to train the model:

<img width="1018" alt="Screenshot 2024-06-11 at 4 49 53 PM" src="https://github.com/BrandonDavidson/Project_two-Team_Four/assets/159976118/c9295703-8f57-44aa-b0bb-8cb093d39b83">
<img width="1013" alt="Screenshot 2024-06-11 at 4 50 49 PM" src="https://github.com/BrandonDavidson/Project_two-Team_Four/assets/159976118/ae47066b-95da-40cf-98d1-14be27194df8">
<img width="1006" alt="Screenshot 2024-06-11 at 4 51 40 PM" src="https://github.com/BrandonDavidson/Project_two-Team_Four/assets/159976118/f2178e8e-c3ed-40af-ad43-7a11ac3a9976">

# Visualization

The first graph showing below is the Confusion Matrix: 

<img width="802" alt="Screenshot 2024-06-11 at 4 53 28 PM" src="https://github.com/BrandonDavidson/Project_two-Team_Four/assets/159976118/40ee948e-04b6-466f-b015-52dd23f42a4d">

Following the Confusion Matrix will be the Decision Tree Model: We have uploaded a PDF file of the Decision Tree allowing you to zoom into each of the boxes below to see how the model will make its decisions.  

<img width="982" alt="Screenshot 2024-06-11 at 4 54 21 PM" src="https://github.com/BrandonDavidson/Project_two-Team_Four/assets/159976118/8fce2c42-1578-4e43-a28a-4ce6a191efc6">

The last graph is the Feature Importance: 

<img width="984" alt="Screenshot 2024-06-11 at 4 54 56 PM" src="https://github.com/BrandonDavidson/Project_two-Team_Four/assets/159976118/3b7f46e7-d44b-4711-9a38-cf7d8a28f47f">
