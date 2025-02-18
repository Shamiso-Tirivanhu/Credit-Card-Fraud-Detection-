# Credit Card Fraud Detection using Python and Machine Learning

## Table of Contents
1. [Project Overview](#project-overview)
2. [Dataset](#dataset)
3. [Data Preprocessing](#data-]re]rocessing)
4. [Model training](#model-training)
5. [Model Evaluation](#model-evaluation)
6. [Results and Insights](#results-and-insights)
7. [How to run the project](#how-to-run-the-project)
8. [Conclusion](#conclusion)

## 1. Project Overview

This project aims to detect fraudulent credit card transactions using machine learning techniques.
The dataset used for this project is a real-world dataset containing transactions made by credit cards, with a classification of whether each transaction is fraudulent or not.

## 2. Dataset 

The dataset used is creditcard.csv, which consists of:

- A large number of transactions with various features.

- A highly imbalanced distribution of fraudulent vs. non-fraudulent transactions.

## 3. Data Preprocessing

- Loading the dataset using Pandas.

- Checking for missing values and handling them accordingly.
  
- The dataset was largely imbalanced. To circumvent this, the data set was split into fraudent transactions(fraud) and normal transactions(legit).

- Feature scaling and selection.

- Splitting the dataset into training and testing sets.


![Image_Alt](https://github.com/Shamiso-Tirivanhu/Credit-Card-Fraud-Detection-/blob/6f2c0f7b4fabbaafa4593880bc7d54e584c587a5/Imbalanced%20dataset-%20%20Credit%20Card%20Fraud%20detection.png)
  

## 4. Model Training

- Logistic Regression is used as a baseline model.

- Other possible models can be explored, such as Decision Trees, Random Forest, and Neural Networks.

## 5. Model Evaluation

- The performance of the model is assessed using accuracy, precision, recall, and F1-score.

- Addressing the issue of imbalanced data using techniques like SMOTE or class weighting.


![Image_Alt](![image]( https://github.com/Shamiso-Tirivanhu/Credit-Card-Fraud-Detection-/blob/47723804aa79fdd698f1e425bb18d4fc3aa4c7c0/Credit%20Card%20Fraud%20Detection%20picture.png)



What we can see from the image above is that the model works perfectly as the training dataset accuracy score is not significantly larger or miniscule than the testing data set. The model does not have issue with underfitting or overfitting.

## 6. Results and Insights

- The model works perfectly as the training dataset accuracy score is not significantly larger or miniscule than the testing data set.
  
- The model does not have issue with underfitting or overfitting.

- There wre not a lot of issues with 

- Possible improvements and future work.

## 7. How to run the Project

1. Install the required dependencies using pip install -r requirements.txt.

2. Run the Jupyter Notebook step by step.

3. Evaluate the model’s performance and make necessary modifications.

## 8. Conclusion

This project demonstrates the effectiveness of machine learning techniques in detecting fraudulent transactions.
Future improvements can include trying different models, tuning hyperparameters, and using deep learning techniques.
Furthermore, the project also demonstrated that logistic regression is the best algorithm to use as this datset dealt with binary values.
