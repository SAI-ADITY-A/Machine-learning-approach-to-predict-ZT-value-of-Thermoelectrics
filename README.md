# Machine-learning-approach-to-predict-ZT-value-of-Thermoelectrics

## Overview 

Thermoelectric materials have received much attention for energy harvesting devices and power generators. However, discovering novel high-performance thermoelectric materials is a challenging task due to the diversity and the structural complexities of the thermoelectric materials containing alloys and dopants. For efficient data-driven discovery of novel thermoelectric materials, this project aims to predict the figure of merit (ZT value) of new thermoelectric materials using machine learning techniques. We utilize the XGBoost regression model and leverage existing data from the ESTM (Electronic Structure Theory of Materials) database.

Reference: https://www.nature.com/articles/s41524-022-00897-2

## Pre-requisites

-> Python 3.8 or above

-> Jupyter Notebook

## Data

The dataset is sourced from the ESTM database.
The data should be in CSV format with the following columns:

• Material properties (e.g., chemical composition, crystal structure)

• ZT value

## Project Workflow

1. Data Collection: Collect and organize data from the ESTM database.

2. Data Preprocessing: Clean and preprocess the data.

3. Feature Engineering: Create relevant features for the model.

4. Model Training: Train the XGBoost regression model.

5. Model Evaluation: Evaluate model performance and refine as necessary.

6. Prediction: Predict ZT values for new materials.


