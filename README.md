# Shipment Status Prediction using Machine Learning

## Problem Statement
The goal of this project is to develop a machine learning model that accurately predicts the product shipment status. The prediction will determine whether the product will be delivered on time or not based on historical data.

## Projret Flow 
1. Data Collection
2. Data Preprocessing
3. Base Model
4. Class Imbalance Treatment
5. Exploratory Data Analysis (EDA) - Outliers, Skewness Treatment
6. Model Building
7. Second DataFrame
8. Feature Selection
9. Final DataFrame

## Dataset Insights
- The dataset contains 10099 rows and 12 columns.
- The target variable is "Reached_on_time," which is categorical with values one and zero.
- There are 11 independent columns such as Warehouse Block, Cost of the Product, Weight of Product, Shipment Mode, etc., which impact the target variable.

## Repository Structure
- `data/`: Contains the dataset used for training and testing.
- `notebooks/`: Jupyter notebooks for data preprocessing, model building, and evaluation.
- `src/`: Python scripts for utility functions and model implementation.
- `README.md`: Overview of the project, instructions for setup, and usage.

## Installation
1. Clone the repository:
   ```bash
   git clone https://github.com/your_username/Shipment-Status-Prediction-using-ML.git
