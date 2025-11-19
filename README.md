# Synthetic-Data-Creation-Using-SDV

The SDV project is a comprehensive Python library designed to generate realistic synthetic data for tabular, relational, and time-series datasets, using advanced machine learning models to emulate the statistical properties and relationships of real data, enabling privacy-preserving data sharing, augmentation, and analysis.

# Project Overview

This project uses the Synthetic Data Vault (SDV) library to generate high-quality synthetic data based on the Automobile dataset. Leveraging advanced machine learning models like GANs, SDV learns the relationships between features and the target variable to create realistic synthetic data for use in model training, data augmentation, and privacy-sensitive scenarios.

# Dataset Description

  1) The Automobile dataset includes car attributes such as:

  2) Target variable: mpg (miles per gallon)

  3) Features: cylinders, displacement, horsepower, weight, acceleration, model_year, origin

  4) Unique identifiers like name are excluded from modeling.

# How to Use

  1) Install the SDV library with pip install sdv.

  2)Load and preprocess the Automobile dataset.

  3)Train an SDV synthesizer (e.g., CTGAN) on the real data.

  4)Generate synthetic samples as needed for your analysis or model building.

# Benefits

  1)Addresses data scarcity and augment training sets

  2)Preserves feature relationships and data privacy

  3)Enables scalable synthetic data generation for diverse use cases



<img width="1911" height="1071" alt="Screenshot 2025-11-19 162323" src="https://github.com/user-attachments/assets/cd06cf32-f204-4ec5-9887-f9d93f08c330" />
