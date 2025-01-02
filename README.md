# Codtech-Internship-task-1
Name: VISHAL BHALCHANDRA SURYAWANSHI/n
Company: CODTECH IT SOLUTIONS
ID: CT12WEJN
Domain: DATA SCIENCE
Duration: December 2024 to March 2025

Overview of the project 
Project: Exploratory Data Analysis(EDA) on Tips Dataset

Objectives: perform exploratory data analysis (EDA) on the "tips" dataset. 

Key Activities:

1. Data Cleaning:
Dataset Inspection:
Loaded the dataset and checked its structure using .info() to understand column data types and detect any missing values or inconsistencies.
Displayed the statistical summary with .describe() to identify ranges, means, and potential outliers in numerical columns.
Initial Exploration:
Checked the first few rows of the dataset to ensure the data was loaded correctly and to get a glimpse of its structure.

2. Data Visualization:
Distribution Analysis:
Created histograms for total_bill and tip columns to analyze their frequency distributions and identify patterns, such as skewness or multimodality.
Overlayed kernel density estimates (KDE) on histograms for a smoother visualization of data trends.
Scatter Plot:
Plotted a scatter plot to analyze the relationship between total_bill and tip, using color (hue='sex') to add a demographic dimension (gender differences).
Visualization Enhancements:
Added appropriate titles, axis labels, and legends to ensure readability and clear communication of insights.

3. Correlation Analysis:
Correlation Computation:
Calculated the pairwise correlation between numerical features (e.g., total_bill, tip, size) using the .corr() method.
Heatmap Visualization:
Visualized the correlation matrix using a heatmap with annotations to easily identify the strength and direction of relationships (e.g., strong positive or negative correlations).

Technologies used:

Python Programming Language:
Pandas (import pandas as pd):
NumPy (import numpy as np):
Matplotlib (import matplotlib.pyplot as plt):
Seaborn (import seaborn as sns):

