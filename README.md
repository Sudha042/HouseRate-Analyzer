# HouseRate Analyser

## Overview
This project uses machine learning to predict house prices based on a dataset with **7120 rows** and **108 features**. The **Random Forest** algorithm was selected for this task because it provided better accuracy compared to other models like Decision Tree and Linear Regression.

## Table of Contents
- [Introduction](#introduction)
- [Dataset](#dataset)
- [Features](#features)
- [Model Selection](#model-selection)
- [Performance Evaluation](#performance-evaluation)
- [How to Use](#how-to-use)
- [Project Link](https://colab.research.google.com/drive/1NSLtMlMykhOJk-p0ryHSzjv18vWIn4XI?usp=sharing)
- [Conclusion](#conclusion)

## Introduction
House price prediction is a valuable application of machine learning that assists home buyers, sellers, and investors by providing accurate price estimates based on various factors. This project implements a **Random Forest** algorithm, which was found to deliver the best performance on this dataset.

## Dataset
- **Rows**: 7120 (property records)
- **Columns (Features)**: 108
- **Target Variable**: House price

The dataset contains features related to property characteristics, location, and neighborhood statistics. The data was preprocessed to handle missing values, outliers, and categorical variables.

## Features
Key categories of features:
- **Location**: Proximity to schools, public transportation, shopping centers, etc.
- **Property Characteristics**: Number of bedrooms, square footage, lot size, etc.
- **Neighborhood**: Crime rates, average income, etc.

For a detailed description of the features, refer to the `features_description.txt` file in the repository.

## Model Selection
The following models were considered:
- **Linear Regression**
- **Decision Tree**
- **Random Forest**

After comparison, the **Random Forest** algorithm was chosen for its ability to handle high-dimensional data and produce the most accurate predictions.

## Performance Evaluation
The Random Forest model was evaluated using:
- **Mean Absolute Error (MAE)**
- **Root Mean Squared Error (RMSE)**
- **R-squared (R²)**

The model performed better than the alternatives, achieving lower errors and higher R² scores, which indicate the strength of its predictive accuracy.

## How to Use

### Prerequisites
- Python 3.x
- Required packages: `pandas`, `numpy`, `scikit-learn`, `matplotlib`

### Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/house-price-prediction.git
   cd house-price-prediction
