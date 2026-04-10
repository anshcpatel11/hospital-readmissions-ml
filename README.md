# Predicting 30-Day Hospital Readmission Risk Using Machine Learning

This project was completed for EECE 5644 and explores the problem of predicting 30-day hospital readmission using the Diabetes 130-US Hospitals dataset.

## Project Overview
The goal of this project is to predict whether a patient will be readmitted within 30 days of discharge. The problem is framed as a binary classification task and evaluated using multiple machine learning models.

## Models Used
- Logistic Regression
- Decision Tree
- Random Forest
- Gradient Boosting
- K-Nearest Neighbors
- Neural Network

## Best Model
The tuned Logistic Regression model provided the best overall balance of performance for this imbalanced dataset.

## Dataset
This project uses the Diabetes 130-US Hospitals dataset from the UCI Machine Learning Repository:
https://archive.ics.uci.edu/ml/datasets/diabetes+130-us+hospitals+for+years+1999-2008

Place the dataset file `diabetic_data.csv` inside the `data/` folder before running the notebook.

## Repository Structure
- `notebooks/` contains the final notebook
- `data/` contains dataset instructions
- `report/` contains the final report

## How to Run
1. Clone this repository
2. Install the required packages
3. Download the dataset and place it in the `data/` folder
4. Open and run the notebook in `notebooks/`

## Requirements
See `requirements.txt` for the Python packages used in this project.
