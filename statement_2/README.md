# 🛡️ Intelligent Military System: Predicting Troop Betrayal

![Project Banner](https://github.com/kaustubh202/onyttig/raw/main/banner.png)

## Overview

This project aims to build an **intelligent decision-making system** to predict potential troop betrayal in military settings. By analyzing a wide range of soldier metrics and external factors, the system can provide valuable insights and risk assessments for military strategists. The data used in this project has been **synthetically generated** using **CTGAN**, ensuring robust and diverse datasets to simulate real-world scenarios.

## Table of Contents

- [Project Background](#project-background)
- [Features](#features)
- [Data Generation](#data-generation)
- [Model Workflow](#model-workflow)
- [Results](#results)

## Project Background

In warfare, predicting betrayal is crucial to maintaining military strength and integrity. This project leverages an advanced decision-making system to evaluate several metrics, including:

- **Personal Metrics**: Information like rank, education, and personal history.
- **Behavioral Metrics**: Factors such as physical and mental health, and history of grievances.
- **Service Metrics**: Records of active duty, service time, and mission success rate.
- **Performance Metrics**: Historical performance in active and passive duties.
- **Demographic Metrics**: Age, location, and educational background.
- **External Factors**: Influence of external conditions like warfare and political climate.

## Features

- **🔍 Comprehensive Analysis**: Uses a multi-metric system to assess betrayal risk based on 24 aspects.
- **📈 Synthetic Data Generation**: CTGAN is utilized to create realistic datasets for analysis and model training.
- **📊 Risk Assessment**: Provides a clear assessment of betrayal likelihood with detailed metrics.
- **🔄 Dynamic Insights**: Offers actionable recommendations for mitigating betrayal risk.

## Data Generation

### Using CTGAN for Synthetic Data

Due to the sensitive nature of military data, real-world datasets are often unavailable. We used **CTGAN** (Conditional Tabular GAN) to generate synthetic records that mimic real-world soldier data. This synthetic dataset includes 500 profiles with various attributes, providing a robust basis for betrayal prediction.

## Model Workflow

The project uses a structured approach to assess betrayal risk, incorporating various metrics such as:

1. **Service Metrics**: Analyzing duty records, mission success rates, and current postings.
2. **Behavioral Metrics**: Evaluating physical and mental health, corruption levels, and campaign involvement.
3. **Performance Metrics**: Reviewing grievances filed, unexplained absences, and recent task performance.
4. **Personal and Demographic Metrics**: Considering family history, dependencies, and demographic factors.
5. **External Factors**: Assessing the influence of external conditions like political instability or financial incentives.

## Results

A detailed report of the betrayal prediction, including likelihood scores and behavioral analysis, can be found in the `results/` directory. The system flags individuals with a betrayal likelihood above 85% for further review.
