# Air-Quality-Pollution-Assessment

# 🌍 Air Quality and Pollution Assessment

This project focuses on assessing air quality across various regions using a machine learning approach. The dataset, sourced from [Kaggle](https://www.kaggle.com/datasets/mujtabamatin/air-quality-and-pollution-assessment), captures critical environmental and demographic factors that influence pollution levels. The goal is to predict the **Air Quality Level** of a region based on environmental features.

---

## 📊 Dataset Overview

The dataset consists of **5000 samples**, with the following features:

- **Temperature (°C)**: Average temperature of the region  
- **Humidity (%)**: Relative humidity recorded in the region  
- **PM2.5 Concentration (µg/m³)**: Fine particulate matter levels  
- **PM10 Concentration (µg/m³)**: Coarse particulate matter levels  
- **NO₂ Concentration (ppb)**: Nitrogen dioxide levels  
- **SO₂ Concentration (ppb)**: Sulfur dioxide levels  
- **CO Concentration (ppm)**: Carbon monoxide levels  
- **Proximity to Industrial Areas (km)**: Distance to the nearest industrial zone  
- **Population Density (people/km²)**: Number of people per square kilometer  

**Target Variable: Air Quality Levels**

- `Good`: Clean air with low pollution levels  
- `Moderate`: Acceptable air quality with some pollutants present  
- `Poor`: Noticeable pollution that may cause health issues for sensitive groups  
- `Hazardous`: Highly polluted air posing serious health risks

---

## 🛠️ Preprocessing Steps

- Applied **SMOTE (Synthetic Minority Over-sampling Technique)** to balance the dataset due to class imbalance in air quality levels.
- Performed standard data cleaning and feature scaling as necessary.

---

## 🤖 Machine Learning Model

- **Algorithm Used**: Random Forest Classifier
- **Accuracy Achieved**: **94%**

Random Forest was selected for its robustness and ability to handle both numerical and categorical data effectively.

---

## 📈 Results

- Achieved high accuracy in classifying air quality levels.
- The model shows strong generalization on the test set.
- Feature importance analysis highlights key contributors such as PM2.5, PM10, and proximity to industrial areas.

---

## 📁 Files

- `air_quality_analysis.ipynb`: Main notebook containing data analysis, preprocessing, model training, and evaluation.
- `README.md`: Project overview and documentation.

---


