# Chevron Corporation - MRO analysis with Data Science

This project was one of my first interactions with Data Science in 2019. I enrolled in an extracurricular course to quickly grasp the basics of the field. As part of the course, I completed a hands-on capstone project with Chevron Corporation, using data from the MRO department to identify opportunities for reducing operating expenses.

## Table of Contents
1. [About the Project](#about-the-project)
2. [Features](#features)
3. [Project Structure](#project-structure)
4. [Data](#data)
5. [Insights](#insights)

## About the project

The class received data related to Equipment, Equipment Status History, and Work Orders. The goal was to uncover opportunities within the raw data by applying core data science techniques, including data cleaning, descriptive statistics, PCA, regression analysis, machine learning, and data visualization.

The conclusion was that the most important variables are assistance rate (failure/breakdown rate), time to terminate assistance and cost. From the PCA analysis, it was concluded that Cost and Class are related to Usuario, Red Vertido, Instalación, Area Geografica, Proyecto and Cantidad de Materiales.

## Features

### 🪐 **Jupyter Notebooks**
- Data cleaning and wrangling
- PCA analysis
- Deep Learning 

### 📂 **Datasets**
- Both raw data and cleaned data for analysis.

### 📊 **Insights and Conclusions**
- Summary and conclusions

## Project Structure

This repository is organized as follows:

- `data/`: Contains datasets and raw data.
  - `raw data`: Contains all the raw data received by Chevron Corporation.
  - `clean data`: Contains all the cleaned data received by Chevron Corporation.
  - `dictionary`: Data dictionary and mapping.
- `notebooks/`: Jupyter Notebooks for analysis and modeling.
  - `1_data_exploration_and_preprocessing.ipynb`: Notebook with basic data exploration and preprocessing.
  - `2_PCA_analysis_part_1.ipynb`: Notebook with PCA Analysis.
  - `2_PCA_analysis_part_2.ipynb`: Notebook with PCA Analysis.
  - `3_deep_learning.ipynb`: Notebook with Deep Learning.
- `docs/`: Documentation and summary presentation..
- `requirements.txt`: Dependencies required for the project.
- `README.md`: The main project documentation (this file).


## Data
This project relies on datasets stored in the `data/` directory. Below are the details:

---

### **Included Datasets**
The following datasets are included in the repository:
- **`parts_filtered.csv`**: The data consists of reports about maintenance of disposal systems. There are 30 variables and cost.  
- **`dictionary and master data mapping.csv`**: Dictionary and mapping for the parts_filtered.csv file.
