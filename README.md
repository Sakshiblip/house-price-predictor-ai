[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/Sakshiblip/house-price-predictor-ai/blob/main/predicting_housing_market_trends_with_AI.ipynb)
# Predicting Housing Market Trends with AI 🏠

This repository contains a machine learning project focused on predicting real estate prices using regression techniques. By analyzing various architectural and environmental features, this project builds a model capable of estimating property values with high precision.

## 📌 Project Overview
The goal of this project is to apply advanced regression algorithms to predict housing prices. It covers the entire data science pipeline, from handling skewed data and feature engineering to training high-performance gradient boosting models like XGBoost.

## 🚀 Key Features
* **Data Preprocessing:** Robust handling of missing values and categorical encoding for over 70 features.
* **Skewness Correction:** Identification and transformation of skewed numerical features to improve model performance.
* **Exploratory Data Analysis (EDA):** Visualization of correlations between house features (like Square Footage, Neighborhood, and Year Built) and the final Sale Price.
* **Advanced Modeling:** Implementation of multiple regression models, including:
    * **Linear Regression:** For baseline performance.
    * **XGBoost (Extreme Gradient Boosting):** For high-accuracy predictions.
* **Performance Evaluation:** Accuracy assessment using Mean Squared Error (MSE), Mean Absolute Error (MAE), and R-squared ($R^2$) scores.

## 🛠️ Tech Stack
* **Language:** Python 3.x
* **Libraries:**
    * `Scikit-learn`: Model building and preprocessing.
    * `XGBoost`: Advanced gradient boosting.
    * `Pandas` & `NumPy`: Data manipulation.
    * `Matplotlib` & `Seaborn`: Statistical data visualization.
    * `Scipy`: Statistical analysis and skewness handling.

## 📊 Analysis Workflow
1.  **Exploration:** Analyzing the distribution of the target variable (`SalePrice`).
2.  **Feature Engineering:** Encoding ordinal variables and creating dummy variables for nominal features.
3.  **Scaling:** Using `StandardScaler` to normalize feature distributions.
4.  **Training:** Splitting data into training and validation sets to ensure model generalizability.
5.  **Submission:** Generating final predictions for competition-style evaluation.

## 📂 Dataset
The project utilizes the **House Prices: Advanced Regression Techniques** dataset, which includes features describing almost every aspect of residential homes in Ames, Iowa.

## 📖 How to Use
1.  **Clone the Repo:**
    ```bash
    git clone [https://github.com/your-username/housing-market-prediction.git](https://github.com/your-username/housing-market-prediction.git)
    ```
2.  **Install Dependencies:**
    ```bash
    pip install pandas numpy matplotlib seaborn scikit-learn xgboost scipy
    ```
3.  **Run the Notebook:**
    Open `predicting_housing_market_trends_with_AI.ipynb` in Google Colab or Jupyter Notebook to see the training process and results.

---
*Developed as part of a Data Science exploration into Predictive Analytics and AI.*
