# Analyzing Apple Health Data

This repository contains the term project for **CS 210 – Introduction to Data Science**.  
The project focuses on analyzing personal **Apple Health** data to understand long-term
patterns in physical activity and to examine whether academic workload affects daily activity levels.

---

## Project Overview

The goal of this project is to explore and analyze personal health data collected from
Apple Health, including:

- Step count
- Distance walked
- Basal energy burned
- Active energy burned

The analysis investigates whether changes in academic workload—particularly during
final exam periods—have a significant impact on physical activity. The project also
includes a machine learning component to predict average monthly step counts.

---

## Dataset

The dataset consists of **personal Apple Health records** exported in `.xml` format.
Only relevant activity-related data were extracted and used in the analysis.

**Data sources include:**
- Step Count
- Distance
- Basal Energy Burned
- Active Energy Burned

> Note: The raw Apple Health data is **personal and not included** in this repository.

---

## Methodology

The project is divided into three main parts:

### 1. Data Parsing and Preparation
- Parsed Apple Health `.xml` files
- Filtered relevant activity data
- Converted timestamps into year, month, and day
- Generated structured pandas DataFrames
- Merged related datasets for correlation analysis

### 2. Exploratory Data Analysis & Visualization
- Visualized monthly trends in step count and distance
- Examined correlations between different activity metrics
- Analyzed activity patterns during academic final exam periods
- Used statistical summaries and heatmaps to explore relationships

### 3. Machine Learning
- Framed the problem as a regression task
- Split data into training (80%) and test (20%) sets
- Trained a **Decision Tree** model to predict average monthly step count
- Tuned hyperparameters (`max_depth`, `min_samples_split`) to avoid overfitting
- Achieved an accuracy of approximately **85%**

---

## Key Findings

- Step count and distance show strong correlation.
- Physical activity tends to decrease during certain months, but **not consistently
  during academic final exam periods**.
- Academic workload does **not** appear to be a strong determinant of physical activity.
- The machine learning model successfully captures monthly activity trends.

---

## Tools & Technologies

- Python
- pandas
- NumPy
- Matplotlib / Seaborn
- scikit-learn
- Jupyter Notebook

---

## Notes

This project was completed for educational purposes as part of the CS 210 course.
The notebook reflects the original experimental setup and has been preserved without
refactoring.

---

