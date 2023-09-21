# Supply-Chain-Management
# Supply Chain Management Project

![Project Image](project_image.png)

## Table of Contents
- [Introduction](#introduction)
- [Project Overview](#project-overview)
- [Key Steps](#key-steps)
- [Key Insights](#key-insights)
- [Recommendations](#recommendations)
- [Getting Started](#getting-started)
- [Dependencies](#dependencies)
- [Usage](#usage)
- [Contributing](#contributing)
- [License](#license)

## Introduction

This repository contains the code and documentation for a supply chain optimization project for a Fast Moving Consumer Goods (FMCG) company. The project aims to address the challenge of optimizing supply quantities from various warehouses to meet market demand effectively.

## Project Overview

In today's fast-paced consumer goods industry, efficient supply chain management is essential for businesses to thrive. The FMCG sector, in particular, faces the challenge of balancing supply with ever-changing demand patterns. An imbalance in supply and demand not only incurs inventory costs but also poses a significant financial risk to companies.

The primary goal of this project is to develop a data-driven solution that optimizes the supply quantity of instant noodles from each warehouse across the country. To achieve this, we utilized historical data, employed various data science techniques, and applied machine learning algorithms to predict the optimum product weight to be shipped from each warehouse.

## Key Steps

- **Data Exploration and Preprocessing:** We started by exploring the dataset, identifying the types of features, and checking for missing values. Data cleaning and preprocessing were performed to ensure the dataset's quality and consistency.

- **Feature Engineering:** We engineered relevant features to enhance the predictive power of our models and to uncover potential relationships between variables.

- **Model Development:** We applied multiple machine learning algorithms, including Linear Regression, Random Forest, Gradient Boosting, and Support Vector Machines, to predict the optimal product weight to be shipped from each warehouse. These models were trained on historical data to make predictions.

- **Model Evaluation:** Each machine learning model was evaluated using appropriate metrics, such as Mean Squared Error (MSE), on a test dataset to assess its effectiveness in optimizing supply quantities. The model's performance provided insights into its predictive power.

- **Data Visualization:** We created visualizations to communicate important insights, including feature importance, model performance, and relationships between variables.

## Key Insights

- **Variation in Demand and Supply:** The data revealed significant variations in demand and supply across different regions and warehouses.

- **Model Performance:** The machine learning models provided valuable predictions for optimizing supply quantities. The MSE metric indicated the level of error in the predictions, which is crucial for making informed decisions.

- **Feature Importance:** Some features, such as the number of competitors in the market, distance from the production hub, and the number of retail shops, showed notable importance in predicting supply quantities.

- **Warehouse Establishment Years:** The establishment years of warehouses varied, highlighting the historical context of each facility.

## Recommendations

Based on the insights gained from this project, we offer the following recommendations to the FMCG company:

- **Model Integration:** Implement the best-performing machine learning model(s) into your supply chain management system to optimize supply quantities based on historical data and predictive analytics.

- **Demand Forecasting:** Enhance demand forecasting capabilities to better align supply with market demand, reducing the risk of overstock or understock situations.

- **Competitive Analysis:** Continuously monitor and analyze the competitive landscape to adapt supply chain strategies accordingly.

- **Efficiency Improvement:** Consider process improvements and technology enhancements to optimize warehouse operations, transportation, and distribution.

- **Data-Driven Decision-Making:** Embrace data-driven decision-making as an ongoing practice to respond to changing market dynamics effectively.

## Getting Started

To get started with this project, follow these steps:

1. Clone this repository: `git clone https://github.com/yourusername/supply-chain-optimization.git`
2. Navigate to the project directory: `cd supply-chain-optimization`
3. Set up your Python environment and install the required dependencies.

## Dependencies

Ensure you have the following dependencies installed:

- Python 3.x
- Pandas
- NumPy
- Scikit-Learn
- Matplotlib
- Seaborn
- Jupyter Notebook (for running the project notebooks)

