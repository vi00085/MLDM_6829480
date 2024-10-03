# ScubeHK

This repository contains coursework and related files for the **ScubeHK** project, which covers tasks related to customer churn prediction and stroke prediction using machine learning techniques. The repository also includes related Prolog scripts and setup files for prediction tasks.

## Table of Contents
- [Project Overview](#project-overview)
- [Files Included](#files-included)
- [Prerequisites](#prerequisites)
- [Installation and Setup](#installation-and-setup)
- [Running the Project](#running-the-project)
- [Results](#results)

## Project Overview

The **ScubeHK** project focuses on two predictive models:

1. **Customer Churn Prediction**: Predicting if a customer will churn based on demographic and service usage data.
2. **Stroke Prediction**: Predicting the likelihood of a stroke occurrence based on healthcare dataset features.

Both tasks utilize supervised machine learning methods, including data preprocessing, exploratory data analysis, and the application of machine learning algorithms such as Random Forest Classifiers.

## Files Included

- **`customer.ipynb`**: Jupyter Notebook for customer churn prediction analysis and modeling.
- **`Stroke_Prediction_Coursework.ipynb`**: Jupyter Notebook for stroke prediction analysis and modeling.
- **`Telco-Customer-Churn.csv`**: Dataset used for customer churn prediction.
- **`healthcare-dataset-stroke-data.csv`**: Dataset used for stroke prediction.
- **`Setup_Churn_Prediction.pdf`**: Documentation outlining the setup and steps involved in customer churn prediction.
- **`Setup_Stroke_Prediction.pdf`**: Documentation outlining the setup and steps involved in stroke prediction.
- **`aleph.pl`**: Prolog script related to inductive logic programming.
- **`aleph_original.pl`**: Original Prolog script used for a logic-based learning approach.
- **`train_facts.pl`**: Prolog script containing facts used in the logic-based learning process.
- **`generate_so.py`**: Python script to generate shared objects, potentially related to the integration of Prolog-based logic systems.

## Prerequisites

- Python 3.12
- Jupyter Notebook
- Required Python libraries such as `numpy`, `pandas`, `matplotlib`, `seaborn`, `scikit-learn`
- Prolog interpreter for `.pl` files

## Installation and Setup

1. Clone the repository:
   ```bash
   git clone https://github.com/vio0085/MLDM_6829480.git

2. Navigate to the project directory:
     cd MLDM_6829480

3. Install the required Python packages:
     pip install -r requirements.txt

## Running the Project

- Open the Jupyter Notebook for customer churn or stroke prediction.
- Follow the steps in the notebook to load the datasets, preprocess the data, and run the predictive models.
- For Prolog-based logic programming, run the .pl files using a Prolog interpreter (such as SWI-Prolog).

## Results

- Customer Churn Prediction: Predicts whether a customer is likely to churn based on several features like gender, tenure, monthly charges, and more.
- Stroke Prediction: Predicts the likelihood of a stroke based on factors such as age, BMI, glucose levels, and medical history.
- Model results, confusion matrices, and classification reports are displayed in the Jupyter Notebooks for each task.
