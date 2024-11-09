# Advancing Predictive Maintenance for Vehicle Systems Using Multimodal and Real-Time Data

## Project Overview

Welcome to the **Predictive Maintenance for Vehicle Systems** project! This repository contains a series of data exploration, statistical analysis, and machine learning experiments aimed at enhancing predictive maintenance models for the automotive and transportation sectors. By integrating the **MetroPT dataset** and **NASA’s Turbofan Engine Degradation Simulation Data**, this project explores how multimodal machine learning models can improve the early detection of vehicle system failures.

The primary objective of this project is to analyze how multimodal data—combining metro system operational data with automotive telemetry and real-time sensor data—can improve predictive maintenance models. Using machine learning algorithms, this study investigates the potential of these models to predict system failures, improve maintenance schedules, and reduce unexpected breakdowns.

## Key Components

- **Data Exploration**: Basic exploration of the **MetroPT dataset** and **NASA Turbofan Engine Degradation Data**, including descriptive statistics and visualizations of key variables like failure rates, degradation patterns, and operational conditions.
  
- **Statistical Analysis**: Identification of recurring maintenance patterns and degradation trends. This includes visual correlation analysis to understand how operational settings and sensor measurements contribute to component wear and failure across different transportation modes.

- **Machine Learning**: Implementation of machine learning models, including **Random Forest** and **Support Vector Machine (SVM)**, to predict maintenance needs. Both single-modality (sensor data or operational data) and multimodal approaches are tested to evaluate their impact on predictive accuracy and reliability in vehicle systems.

## Colab Notebook

The primary code for this analysis is contained in the Jupyter Notebook file **Advancing_Predictive_Maintenance.ipynb**. This notebook can be executed in Google Colab, providing an interactive environment where students and researchers can modify parameters and observe real-time results of the predictive maintenance models.

[**Open in Colab**](https://colab.research.google.com/drive/1jFpqHdT2FzVdd1g5KstMsEbXj-PRv9R0)

### Download the Dataset

1. Download the **MetroPT dataset** and **NASA Turbofan Engine Degradation Simulation Data** from Zenodo and the NASA data repository, respectively.
2. Upload the downloaded data files to your Google Colab environment for easy access.

### Running the Notebook

1. Open the **Advancing_Predictive_Maintenance.ipynb** file directly in Google Colab by selecting "Open in Colab" above or by uploading it to your Colab environment.
2. Ensure that all required libraries (e.g., `pandas`, `numpy`, `matplotlib`, `scikit-learn`) are installed within the Colab environment.
3. Execute each cell in the notebook to perform data analysis, visualization, and model training for predictive maintenance.
