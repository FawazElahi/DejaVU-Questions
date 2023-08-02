# DejaVU-Questions ☯️

## Introduction 👋
This project aims to provide a user-friendly interface for comparing the semantic similarity between two questions. The application utilizes a machine learning model trained on questions data to predict whether the provided questions are duplicates or not. 

![Web Application Screenshot](screenshots/web_interf.png)

## How It Works ⚙️
To compare two questions for semantic similarity, follow these steps:

1. Input Questions: Enter two questions you want to compare in the provided text fields. 💬

2. Get Predictions: Click the "Find" button, and the machine learning model will predict whether the questions are duplicates or not. ❓

3. View Results: The application will display the prediction result, indicating whether the questions are semantically similar or not. 👀

## Visuals 📷
Here are two screenshots showcasing the functionality:

<div style="display: flex; justify-content: space-between; gap: 50px;">
  <img src="screenshots/duplicate.png" alt="Duplicate Functionality" >
  <img src="screenshots/not-duplicate.png" alt="Non-Duplicate Functionality">
</div>

## Machine Learning Model 🤖
The machine learning model used in this project is based on the RandomForest classifier, an ensemble learning algorithm. The model is trained on a dataset of question pairs with labeled duplicates. To improve its accuracy, exploratory data analysis and feature engineering techniques have been employed to introduce informative features. 📊