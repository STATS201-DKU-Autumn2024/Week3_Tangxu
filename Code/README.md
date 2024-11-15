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

## Visualization

This project includes key visualizations to help interpret data trends and understand predictive maintenance patterns within the **MetroPT dataset** and **NASA Turbofan Engine Degradation Simulation Data**. Visualizations are designed to provide insights into component degradation, operational conditions, and sensor data trends, all of which contribute to predictive maintenance modeling.

### Example Visualization
- **Time-Series Trends for Sample Unit in NASA Dataset**: This plot illustrates degradation trends for a sample unit over time, highlighting the relationship between operational cycles and sensor readings. Such visualizations help in identifying patterns in component wear and predicting the Remaining Useful Life (RUL) of high-stress components.

![Time-Series Trends for Sample Unit in NASA Dataset](Time-Series%20Trends%20for%20Sample%20Unit%20in%20NASA%20Dataset.JPG)

### Additional Visualizations
Other visualizations in the notebook cover:
- **Failure Rate Over Time**: Shows how failure rates vary across different components and operational settings.
- **Correlation Heatmaps**: Highlights relationships between various sensor readings and operational conditions, aiding in feature selection for the predictive models.

These visualizations enhance the interpretability of the data, allowing for a more comprehensive understanding of factors influencing predictive maintenance in vehicle systems.

## Dataset

This project utilizes two primary datasets to explore and model predictive maintenance:

1. **MetroPT Dataset**: This dataset provides detailed logs on maintenance activities, operational metrics, and failure events from Lisbon’s metro system. It includes key variables that track the conditions and degradation of metro components over time, offering a robust foundation for predictive maintenance modeling in public transportation.

2. **NASA Turbofan Engine Degradation Simulation Data**: This dataset contains real-time sensor readings from simulated turbofan engines under different operational conditions. It captures degradation patterns across high-stress engine components, allowing for real-time analysis and prediction of component failure.

### Data Dictionary
A comprehensive data dictionary describing all relevant variables in each dataset can be found in the [Data](https://github.com/STATS201-DKU-Autumn2024/Week3_Tangxu/tree/main/Data) section of this repository. The data dictionary includes detailed descriptions, data types, and units for each variable, facilitating better understanding and usage of the datasets within the predictive maintenance context.
