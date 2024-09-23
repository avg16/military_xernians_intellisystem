# INNOV8: The Space Saga - Alien Communication Classification

## Introduction

Welcome to our solution for **INNOV8: The Space Saga**, a problem statement developed by ARIES IITD and Eightfold.ai. Our solution focuses on two exciting parts:

1. **Decoding and Classifying Alien Communications** - Classifying alien transmissions based on linguistic and physical attributes.
2. **Predicting Troop Betrayal in the War Against the Phrygians** - Building a decision-making system to predict betrayal within the ranks of soldiers.

---

## Problem Statement Summary

### Part 1: Decoding and Classifying Alien Communications

Upon landing on the planet Xernia, the team intercepts numerous alien messages. We are tasked with decoding these messages and predicting which alien species sent them. 

The data includes:
- **Message**: The intercepted alien message.
- **Number of Fingers**: The species' typical number of fingers.
- **Tail**: Whether the species has a tail (Yes/No).
  
Our goal is to predict the **species** of aliens based on this data using various machine learning techniques.

---

### Part 2: Predicting Troop Betrayal

In the second part, the mission involves identifying soldiers who might betray the cause. This open-ended challenge requires hypothesis building and designing a decision-making algorithm to predict potential traitors within the ranks.

---

## Dataset

For **Part 1**, we were provided with a CSV file containing alien transmissions and additional attributes such as the number of fingers and tail presence. 

For **Part 2**, we conceptualized a custom dataset based on the defined hypotheses for betrayal prediction.

---

## Approach and Methods

### Part 1: Alien Species Classification

We utilized the following techniques:
- **Exploratory Data Analysis (EDA)**: Understand patterns in the alien language and numerical features.
- **Feature Engineering**: Created new features from the text data and utilized number of fingers and tail as categorical inputs.
- **Machine Learning**: Trained models like Decision Trees, Random Forest, and Support Vector Machines to classify the alien species.
- **Evaluation**: Used accuracy metrics and cross-validation to evaluate our predictions.

### Part 2: Predicting Troop Betrayal

Although this part is open-ended, we proposed the following:
- **Hypothesis Building**: Factors like greed, respect, and temptation were considered as betrayal indicators.
- **System Design**: The workflow involves collecting these factors, analyzing them, and ranking soldiers based on betrayal risk using a decision tree model.

---

## Files

- `solution.ipynb`: Contains the code for Part 1 - Alien Communication Classification.
- `result.csv`: The prediction results for Part 1.
- `report.pdf`: Detailed explanation and approach for Part 2 - Betrayal Prediction.
- `README.md`: This file, providing an overview of the entire project.

---

## Usage

To run the code in `solution.ipynb`:

1. Install the required libraries (if not already installed):
   ```bash
   pip install -r requirements.txt
