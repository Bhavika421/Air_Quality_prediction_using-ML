# 🌍 Air_Quality_prediction_using-ML

This repository contains a Jupyter Notebook for analyzing air quality data. The project leverages Python libraries to clean, explore, and visualize air quality metrics, providing insights into environmental conditions.

📄 Project Overview

The primary goal of this project is to analyze and understand air quality data using statistical, machine learning, and visualization techniques. This analysis helps identify trends and patterns in air quality metrics, crucial for environmental monitoring and policymaking. Through this project, I gained hands-on experience in implementing various machine learning algorithms and successfully predicted air quality levels.

📊 Dataset

File: Air_Quality.csv

Description: The dataset contains information on air quality measurements, including various pollutants and environmental parameters.

Source: (Add details about the dataset source if applicable, e.g., open data portal, government agency, etc.)

✨ Features

🔍 Data Exploration:

Summary statistics of the dataset.

Data types and missing values.

Sampling and inspecting key rows.

🧹 Data Cleaning:

Handling missing or inconsistent values.

Removing outliers or irrelevant columns (if applicable).

📈 Data Visualization:

Generating plots to visualize trends and correlations.

Using libraries like Matplotlib and Seaborn for detailed charts.

🤖 Machine Learning Models:

Preprocessing:

Label encoding using LabelEncoder.

Splitting data into training and testing sets with train_test_split.

Regression Models:

Linear Regression (LinearRegression).

Decision Tree Regressor (DecisionTreeRegressor).

Random Forest Regressor (RandomForestRegressor).

Classification Models:

Logistic Regression (LogisticRegression).

Decision Tree Classifier (DecisionTreeClassifier).

Random Forest Classifier (RandomForestClassifier).

K-Nearest Neighbors Classifier (KNeighborsClassifier).

Evaluation Metrics:

Regression: Mean Absolute Error, Mean Squared Error, R-squared Score.

Classification: Accuracy Score, Confusion Matrix.

🎯 Target Variable:

The target variable AQI_Range classifies air quality as "Good", "Unhealthy", "Poor", etc.

Features used for prediction: SOi, Noi, Rpi, SPMi (stored in X2).

🛠️ Tools and Libraries

The following Python libraries are used:

pandas for data manipulation and analysis.

numpy for numerical computations.

matplotlib and seaborn for data visualization.

sklearn for machine learning models and evaluation metrics.

warnings to suppress unnecessary warnings during execution.

🚀 Getting Started

To run this project locally:

Clone this repository:

git clone https://github.com/yourusername/air-quality-analysis.git

Install the required libraries:

pip install pandas numpy matplotlib seaborn scikit-learn

Open the Jupyter Notebook:

jupyter notebook Air_Quality.ipynb

✅ Results

Through this project, I learned to implement various machine learning algorithms and successfully predicted air quality levels as "Good", "Unhealthy", "Poor", etc., based on features like SOi, Noi, Rpi, and SPMi. The results demonstrated the effectiveness of both regression and classification models for air quality analysis.

🔮 Future Scope

Incorporate advanced machine learning techniques for air quality prediction.

Use real-time data for dynamic analysis
