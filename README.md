# 🚦 Smart Traffic Prediction in Kampala City using Machine Learning

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)
[![Python 3.8+](https://img.shields.io/badge/python-3.8+-blue.svg)](https://www.python.org/downloads/)
[![Jupyter Notebook](https://img.shields.io/badge/Jupyter-Notebook-orange.svg)](https://jupyter.org/)

A comprehensive machine learning project for predicting traffic congestion levels in Kampala City, Uganda. This repository contains both the curated dataset and the complete analytical pipeline for intelligent traffic management.

## 📁 Repository Structure
kampala-traffic-dataset/
├── 📊 kampala-smart-traffic.csv # Primary dataset (500 observations)
├── 🧠 Smart Traffic Prediction in Kampala with AI and Machine Learning.ipynb
├── 📄 README.md # Project documentation
└── ⚖️ LICENSE # MIT License

text

## 🎯 Project Overview

This research addresses Kampala City's critical urban mobility challenges by developing an intelligent traffic congestion prediction system. The project implements a complete data science pipeline from data collection to deployed machine learning models, categorizing traffic conditions into four distinct levels: **Low, Medium, High, and Severe**.

### Key Achievements
- **Model Performance**: XGBoost classifier achieved **54.0% accuracy** in multi-class prediction
- **Feature Engineering**: Created **4 domain-specific features** enhancing predictive power
- **Comprehensive Analysis**: Full pipeline from data preprocessing to model interpretation
- **Real-world Application**: Actionable insights for urban traffic management

## 🏗️ Technical Architecture

### Data Pipeline
1. **Data Collection**: 500 observations across 15 major arterial roads
2. **Preprocessing**: Missing value imputation, outlier treatment, data validation
3. **Feature Engineering**: Domain-driven feature creation
4. **Model Training**: Ensemble learning with XGBoost and Random Forest
5. **Evaluation**: Comprehensive performance metrics and interpretation

### Machine Learning Approach
- **Problem Type**: Multi-class classification (4 congestion levels)
- **Algorithms**: XGBoost, Random Forest
- **Validation**: Stratified 70-30 train-test split
- **Metrics**: Accuracy, Precision, Recall, F1-Score, Confusion Matrix

## 📊 Dataset Specification

### Dataset Overview
- **Records**: 500 temporal observations
- **Roads**: 15 major Kampala arterial roads
- **Coverage**: Multiple weeks capturing daily and weekly patterns
- **Features**: 13 original + 4 engineered features

### Feature Categories

| Category | Features | Description |
|----------|----------|-------------|
| **Temporal** | `hour`, `day_of_week`, `is_weekend` | Time-based patterns |
| **Spatial** | `road_name` | Geographic context |
| **Traffic Flow** | `traffic_volume`, `avg_speed_kmh`, `vehicle_density` | Real-time traffic metrics |
| **Incident Data** | `incident_flag`, `incident_type` | Disruption events |
| **Environmental** | `weather_main` | Weather conditions |
| **Infrastructure** | `road_capacity` | Road characteristics |
| **Engineered** | `capacity_utilization`, `flow_efficiency`, `time_period`, `day_type` | Domain-specific features |

### Target Variable
- `congestion_level`: Categorical (Low, Medium, High, Severe)
- **Distribution**: Balanced representation across congestion categories

## 🧠 Machine Learning Implementation

### Model Performance
| Model | Accuracy | Precision | Recall | F1-Score |
|-------|----------|-----------|--------|----------|
| XGBoost | **54.0%** | 0.508 | 0.540 | 0.520 |
| Random Forest | 52.7% | 0.480 | 0.527 | 0.500 |

### Key Insights
- **Top Features**: Capacity utilization (12.9%), vehicle density (12.0%), flow efficiency (8.9%)
- **Best Performer**: XGBoost demonstrated superior classification capability
- **Critical Detection**: High accuracy in identifying 'Severe' congestion conditions

## 🚀 Quick Start

### Prerequisites
```bash
python>=3.8
jupyter>=1.0.0
pandas>=1.3.0
numpy>=1.21.0
scikit-learn>=1.0.0
xgboost>=1.5.0
matplotlib>=3.5.0
seaborn>=0.11.0
Installation & Execution
bash
# Clone repository
git clone https://github.com/David20-source/kampala-traffic-dataset.git
cd kampala-traffic-dataset

# Launch Jupyter notebook
jupyter notebook "Smart Traffic Prediction in Kampala with AI and Machine Learning.ipynb"

# Execute all cells to reproduce complete analysis
