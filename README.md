EDA Text Classification Reproducibility and Contribution
This repository contains the code for reproducing the results of the paper "Easy Data Augmentation Techniques for Boosting Performance on Text Classification Tasks" by Jason Wei and Kai Zou, as well as my contribution using the XGBoost model for text classification.

Overview
The goal of this project is to replicate the results from the EDA paper and extend the methodology by introducing an additional model—XGBoost. This README provides instructions on how to set up the environment, run the code, and understand the outcomes.

Table of Contents
Prerequisites
Installation
Usage
Results
Contributions
License
Prerequisites
Before running the code, ensure you have the following installed:

Python 3.x
Visual Studio Code
Required Python libraries

Reproduce the Original Paper's Results:

Open the EDA_Reproduction.ipynb notebook and run the cells sequentially to reproduce the results of the EDA paper.

Run the XGBoost Contribution:

Open the EDA_XGBoost_Comparison.ipynb notebook and run the cells to execute the XGBoost model on the dataset and compare its performance with the original models discussed in the EDA paper.

Files in the Repository

EDA.ipynb: Code that introduces and evaluates the XGBoost model.

README.md: Instructions for using the repository.
Results
Original EDA Paper Results
Accuracy Improvement: EDA techniques showed an accuracy improvement ranging from 0.8% to 3.0% across various datasets.
Best Accuracy Achieved: Up to 87.5% on the SST-2 sentiment analysis dataset.
XGBoost Model Results
Accuracy: The XGBoost model achieved an accuracy of 54% on the current dataset.
Performance Comparison: The XGBoost model's performance was compared with the results from the EDA paper, and recommendations for further improvement were made.
Contributions
Reproduction of Results: Successfully reproduced the results from the EDA paper using the provided augmentation techniques.
Model Contribution: Introduced XGBoost as an additional model and evaluated its performance against the baseline models in the original paper.

