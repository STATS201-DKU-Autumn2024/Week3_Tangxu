# Advancing Predictive Maintenance for Vehicle Systems Using Multimodal and Real-Time Data

## Project Overview

This project aims to enhance predictive maintenance in vehicle systems by integrating multimodal data sources, specifically using the **MetroPT dataset** and **NASA’s Turbofan Engine Degradation Simulation Data**. The objective is to explore how multimodal machine learning models can improve early detection of system failures and how real-time sensor data contributes to predictive accuracy for high-stress vehicle components, such as engines and braking systems. The study employs models like Random Forest and Support Vector Machine (SVM) to assess predictive effectiveness, analyzing the impact of combined datasets on maintenance predictions.

## Code Structure

This repository includes Jupyter notebooks and related code organized to streamline data preprocessing, exploratory data analysis (EDA), and model implementation. The code is structured as follows:

### `data_preprocessing.ipynb`

- **Purpose**: This notebook handles data cleaning, normalization, and feature extraction for both datasets.
- **Functions**:
  - `clean_data()`: Removes missing values and outliers.
  - `normalize_features()`: Standardizes feature scales for consistent analysis.

### `eda.ipynb`

- **Purpose**: Conducts an exploratory analysis of time-series data, visualizing trends and patterns in failure and degradation metrics.
- **Key Plot**: 
  - *Time-Series Trends for Sample Unit in NASA Dataset*  
  ![Sample Time-Series Trends](Time-Series%20Trends%20for%20Sample%20Unit%20in%20NASA%20Dataset.jpg)
  
### `model_training.ipynb`

- **Purpose**: Implements and compares machine learning models (Random Forest and SVM) to predict maintenance needs based on multimodal data inputs.
- **Features**:
  - `train_model()`: Trains models on both single-modality and combined datasets.
  - `evaluate_model()`: Calculates metrics such as accuracy, precision, and F1 score.

## Data Sources

The datasets used in this project are available publicly and provide a comprehensive foundation for predictive maintenance modeling:
1. **MetroPT Dataset**: A detailed dataset containing logs on metro system maintenance activities, operational conditions, and failure events.
2. **NASA Turbofan Engine Degradation Simulation Data**: Provides real-time sensor data capturing component degradation under varied conditions.

For further information on variable descriptions, please refer to the [Data Dictionary](https://github.com/STATS201-DKU-Autumn2024/Week3_Tangxu/tree/main/Data).

## Repository Link
For access to the full project files and dataset, visit the GitHub repository: [Project Repository](https://github.com/STATS201-DKU-Autumn2024/Week3_Tangxu)

## References
- Veloso, B., Gama, J., Ribeiro, R., and Pereira, P. 2022. "MetroPT: A Benchmark Dataset for Predictive Maintenance." *Zenodo*.
- Saxena, A., & Goebel, K. 2008. "Turbofan Engine Degradation Simulation Data Set." *NASA Prognostics Data Repository*.
