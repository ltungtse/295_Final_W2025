# Predicting Traffic Accident Severity in NYC

## 🚀 Project Overview
This project applies **machine learning models** to predict the severity of traffic accidents in New York City using the **NYC Motor Vehicle Collisions dataset**. The goal is to identify high-risk factors and optimize road safety measures through data-driven insights.

## 📊 Dataset
- **Source**: NYC Open Data (Motor Vehicle Collisions)
- **Size**: ~2.1 million records
- **Features**: Date, time, location, number of injuries, fatalities, contributing factors, etc.

## 🛠️ Methods & Algorithms
- **Data Preprocessing**: Missing value handling, feature engineering, class balancing (SMOTE & undersampling)
- **Machine Learning Models**:
  - Logistic Regression
  - Decision Tree & Random Forest
  - XGBoost (Best Model: 78.2% Accuracy)
  - K-Nearest Neighbors
  - Neural Networks (MLP)
- **Evaluation Metrics**: Accuracy, Precision, Recall, F1-score
- **Feature Importance Analysis**: Decision Tree vs. XGBoost

## 📈 Key Findings
- **XGBoost outperformed all models** with the highest accuracy and computational efficiency (~3s runtime).
- **Feature Importance**:
  - **Top Features**: Vehicle Type (Motorcycles), Contributing Factors (Speeding, Distraction), Borough (Manhattan), Time Trends
- **Impact of Class Balancing**:
  - SMOTE improved recall for minority classes but slightly reduced precision.

## 🛠️ Tech Stack
- **Programming Language**: Python 🐍
- **Libraries Used**:
  - `pandas`, `numpy`, `matplotlib`, `seaborn` (Data Analysis & Visualization)
  - `scikit-learn` (Machine Learning)
  - `imbalanced-learn` (SMOTE & Class Balancing)
  - `xgboost` (Ensemble Learning)
  - `tensorflow` & `keras` (Neural Networks)

## 📂 Repository Structure
 - project-folder/ 
    - │── notebooks/  
       - │├── data_visualization.ipynb # Exploratory Data Analysis (EDA) 
       - │├── modeling.ipynb           # Machine Learning modeling & evaluation
    - │── Heatmap.zip                  # 📥 Download to view the interactive severity map
    - │── severity.html                # Use the link below
    - |── README.md # Project documentation (this file)

### 🔍 Interactive Visualizations
Click the links below to view the interactive maps:
- Heatmap.zip – Unzip and open in a web browser to view the heatmap of collision density.
- **[View Severity Map](https://raw.githack.com/ltungtse/295_Final_W2025/refs/heads/main/severity.html)**

If the link doesn’t work, download the file and open it in a browser manually.
