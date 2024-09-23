# Alien Communication Classification - INNOV8 Challenge

## Introduction

Welcome to our solution for **Part 1: Decoding and Classifying Alien Communications**, from the INNOV8 challenge by ARIES IITD and Eightfold.ai.

In this part of the challenge, we were tasked with classifying alien messages based on the content of their communication, as well as physical characteristics such as the number of fingers and the presence of a tail. Our solution uses machine learning models to predict the alien species based on these features.

---

## Problem Overview

Upon arriving on planet Xernia, your mission is to intercept and decode alien messages. The intercepted messages contain the following attributes:

- **Message**: A short communication in the alien language.
- **Number of Fingers**: The typical number of fingers the alien species has.
- **Tail**: Whether the alien species has a tail (Yes/No).

The objective is to predict the **species** for each message in the test dataset using the above features.

---

## Approach

Our approach involves the following key steps, as detailed in the `.ipynb` file:

### 1. **Data Loading and Exploration**
   - We first loaded the provided dataset (`data.csv`), which contained the alien messages and attributes.
   - A thorough data exploration was performed to understand the structure of the data and check for missing values, data types, etc.
   - Various plots like the histplot, stripplot, heatmap were plotted to gather more knowledge about the data and perform EDA.
   - The data was found to be really simple without sematic relationships between words and that the messages were random.

### 2. **Preprocessing**
   - To prepare the data for machine learning, we cleaned and preprocessed the dataset by:
     - Encoding the categorical data (like the tail attribute) into numerical form.
     - Tokenizing and vectorizing the alien messages into numeric features that could be used by machine learning models. (Not for the final subumission)

### 3. **Feature Engineering**
   - We engineered additional features from the message text and the physical characteristics of the aliens.
   - Tail and the number of fingers were treated as categorical features and converted to numerical representations.
   
### 4. **Model Building**
   - Several machine learning models were tested, including:
     - **Decision Trees**
     - **Random Forest Classifier**
     - **Support Vector Machine (SVM)**
     - **Transformer based Neural Network**
     - **LSTM based neural network**
     - **Manual Classification by self-made algorithm**
   - After evaluating the performance of each model using accuracy metrics and cross-validation, we selected the model with the best results.

### 5. **Prediction and Result Saving**
   - The chosen model was used to predict the alien species for the test dataset.
   - The results were saved in a `submission.csv` file, as required by the problem statement.

---

## How to Run the Code

To run the code provided in `solution.ipynb`, follow these simple steps:

1. **Clone the repository** or download the `solution.ipynb` file.
2. **Install the required libraries** by running:
   ```bash
   pip install pandas scikit-learn numpy

