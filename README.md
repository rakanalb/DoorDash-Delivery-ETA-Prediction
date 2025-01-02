# 🚚 DoorDash Delivery Time Prediction Model

> A machine learning project that predicts delivery times for food orders from DoorDash using historical data from multiple markets. Built with scikit-learn and optimized through multiple regression models.

![Python](https://img.shields.io/badge/python-v3.9+-blue.svg)
![Scikit-learn](https://img.shields.io/badge/scikit--learn-latest-orange.svg)
![Pandas](https://img.shields.io/badge/pandas-latest-green.svg)
![License](https://img.shields.io/badge/license-MIT-green.svg)

## 📊 Project Overview

This project aims to predict accurate delivery times for food orders by analyzing various factors like:
- Market conditions
- Restaurant categories
- Order details
- Courier availability
- Historical timing data

## 🎯 Results

Model performance (RMSE in minutes):
- Random Forest: 17.29 min
- Linear Regression: 17.46 min
- Gradient Boosting: 17.64 min
- SVR: 19.25 min
- Decision Tree: 23.93 min

## 🛠️ Tech Stack

- **Python**: Core programming language
- **Pandas**: Data manipulation and analysis
- **Scikit-learn**: Machine learning models
- **Matplotlib/Seaborn**: Data visualization
- **Jupyter Notebook**: Development environment

## 📁 Project Structure

```
project/
│
├── Delivery ETA task.pdf       # Project requirements and description
├── Delivery_Times_ETA.ipynb    # Main model development notebook
├── EDA_MiniProject.ipynb       # Exploratory Data Analysis
├── dh_etas.csv                 # Training dataset
├── real_data_etas.csv         # Test dataset
└── submission.csv             # Model predictions
```

## 🔍 Features Used

- Market ID
- Store category
- Order protocol
- Total items
- Subtotal
- Number of distinct items
- Item price range
- Courier availability
- Outstanding orders
- Estimated driving duration

## 📈 Model Pipeline

1. **Data Preprocessing**
   - Missing value imputation
   - Categorical encoding
   - Feature scaling

2. **Model Development**
   - Multiple regression models tested
   - Hyperparameter tuning
   - Cross-validation

3. **Evaluation**
   - RMSE as primary metric
   - Model comparison
   - Error analysis

## 🚀 Getting Started

### Prerequisites
- Python 3.9+
- Jupyter Notebook
- Required packages: pandas, scikit-learn, numpy, matplotlib, seaborn

### Installation

```bash
# Clone repository
git clone <repository-url>

# Install dependencies
pip install -r requirements.txt

# Launch Jupyter Notebook
jupyter notebook
```

## 📊 Usage

1. Open `EDA_MiniProject.ipynb` for data exploration
2. Open `Delivery_Times_ETA.ipynb` for model development
3. Run cells sequentially to reproduce results

## 📝 License

This project is licensed under the MIT License - see the LICENSE file for details.
