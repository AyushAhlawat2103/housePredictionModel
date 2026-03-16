House Price Prediction using Machine Learning
📌 Project Overview

This project builds a machine learning model to predict housing prices based on various features such as income level, number of rooms, population, and housing age. The dataset is preprocessed, engineered with additional features, and used to train regression models to estimate housing prices.

The goal of the project is to demonstrate a complete machine learning workflow including data preprocessing, feature engineering, model training, and evaluation.

📊 Dataset

The dataset used in this project is the California Housing Dataset.

It contains several attributes such as:

Median income

Housing median age

Total rooms

Total bedrooms

Population

Households

Ocean proximity

Median house value (target variable)

Dataset source:
https://github.com/ageron/handson-ml

⚙️ Technologies Used

Python

Pandas

NumPy

Matplotlib

Seaborn

Plotly

Scikit-learn

Jupyter Notebook

🔧 Project Workflow
1️⃣ Data Loading

The housing dataset is loaded directly from an online CSV source using Pandas.

2️⃣ Data Preprocessing

Several preprocessing steps are applied:

Handling missing values

Encoding categorical variables using one-hot encoding

Cleaning the dataset

3️⃣ Feature Engineering

Additional features are created to improve model performance:

rooms_per_household

bedrooms_per_room

population_per_household

These features help capture meaningful relationships within the dataset.

4️⃣ Train-Test Split

The dataset is divided into:

80% training data

20% testing data

This ensures proper evaluation of the model.

5️⃣ Model Training

Two machine learning models are trained:

Linear Regression

Random Forest Regressor

These models are used to predict housing prices based on the selected features.

6️⃣ Model Evaluation

The models are evaluated using standard regression metrics:

Mean Absolute Error (MAE)

Mean Squared Error (MSE)

Root Mean Squared Error (RMSE)

R² Score

Feature importance analysis is also performed for the Random Forest model.

📈 Data Visualization

The project includes several visualizations:

Feature importance plots

Residual distribution plots

Data exploration charts

These help in understanding model performance and data patterns.

🚀 How to Run the Project

Clone the repository

git clone https://github.com/yourusername/house-price-prediction.git

Navigate to the project directory

cd house-price-prediction

Install required libraries

pip install pandas numpy matplotlib seaborn plotly scikit-learn

Run the Jupyter Notebook

jupyter notebook

Open the notebook and execute the cells.

📊 Results

The Random Forest model generally performs better than Linear Regression due to its ability to capture non-linear relationships in the data.

The project demonstrates how machine learning can be used to build predictive models for real estate price estimation.

📌 Future Improvements

Hyperparameter tuning

Adding more advanced models (XGBoost, Gradient Boosting)

Deploying the model using a web application

Using larger real-world datasets

👨‍💻 Author

Ayush
B.Tech Computer Science Engineering
Amity University Noida
