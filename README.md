# Predictive Maintenance of Aircraft Engine using Scikit-Learn

## Table of Contents
- [Introduction](#introduction)
- [Features](#features)
- [Results](#results)
- [Future Work](#future-work)

## Introduction

This project implements a model predicting if the aircraft engine is going to fail in the next cycles. It uses an open data source from Azure AI. 

## Features

- Data preprocessing and exploration of the dataset
- Framing and explaining the problem
- Implementation of a dummy model based on simple logic
- Implementation of a Random Forest model using Scikit-Learn library
- Implementation of a XGBoost model using Scikit-Learn library
- Finetuning of the model, and most important features analysis

## Results

The project demonstrates the effectiveness of XGBoost model in predictive maintenance. We were able to anticipate failures 20 cycles in advance, with an accuracy of 93% and F1 score of 96%.

## Future Work

- Further improve the model, reducing overfitting by focusing on the most important features
- Try other models, using SVM or Neural Networks
- Reframe the problem and explore other possibilities such as trying to predict for more or less than 20 cycles, or turn the problem into a regression problem
- Deploy the model with an API so that it can be used in production
