# 🚗 Car Price Prediction using Machine Learning
# 📊 Project Overview
## The car manufacturing industry in the US is highly competitive with many manufacturers offering a variety of models featuring different specifications. Setting the right price for a car is crucial for maximizing sales and profits. However, determining the optimal price manually is challenging due to the many influencing factors like mileage, manufacturer, horsepower, and more.

## This project leverages machine learning techniques to predict car prices based on important features such as make, horsepower, mileage, and other attributes. By using data-driven models, manufacturers and sellers can set competitive and profitable prices for their cars.

# 📁 Dataset
## Source: Kaggle - Car Dataset by Cooper Union (https://www.kaggle.com/datasets/CooperUnion/cardataset)

The dataset contains ~12,000 records of cars with features including manufacturer, year, engine horsepower, mileage, vehicle size, fuel type, and more.

The dataset was split into training and test sets for model development and evaluation.

It contains specifications for a wide variety of cars, ranging from high-end brands like Bugatti and Lamborghini to more affordable ones like Toyota, Ford, and Honda.

# Business Context & KPIs
The goal is to accurately predict car prices to help sellers set optimal prices that maximize demand and profit. Key performance metrics used to evaluate models:

Mean Absolute Error (MAE)

Mean Squared Error (MSE)

R² values
# 🔍 Project Objectives
Analyze and clean the dataset

Visualize feature relationships with car price

Apply multiple regression models

Evaluate model performance using MAE, MSE, and R² values

Select the best model for car price prediction

# 🛠️ Technologies Used
Python

Pandas, NumPy – data processing

Seaborn, Matplotlib – data visualization

Scikit-learn – machine learning models

Jupyter Notebook – analysis and development

# 📈 Machine Learning Models Applied
Linear Regression

Support Vector Regressor

K-Nearest Neighbors Regressor

PLS Regression

Decision Tree Regressor

Gradient Boosting Regressor

MLP (Neural Network) Regressor

Each model’s predictions are visualized using regplots, and performance is compared using barplots of Mean Absolute Error (MAE), R² values, and Mean Squared Error (MSE).

# Exploratory Data Analysis (EDA)
Chevrolet and Ford are the most frequent manufacturers in the dataset.

Year 2015 had the highest number of manufactured cars.

Missing values existed in features like Market Category, Engine HP, and Engine Cylinders.

Bugatti cars have exceptionally high prices and horsepower.

Negative correlation observed between City Mileage and engine specifications (cylinders and horsepower).

Most cars are automatic transmission and use regular unleaded fuel.

Vehicle sizes are fairly evenly distributed, with compact cars being the most common.

Outliers in highway MPG were removed to improve model accuracy.

Correlation heatmaps reveal strong relationships between horsepower and cylinders, and between city and highway MPG.

# 📊 Visualization Highlights
# Correlation heatmaps
![image](https://github.com/user-attachments/assets/9a6870e7-6d4c-4c21-a3e5-3ffc6d425128)

# Countplot of different car companies
![image](https://github.com/user-attachments/assets/85c4b781-95dd-431f-9bdd-8ea2f48f9f96)
# Countplot of the total cars per different years
![image](https://github.com/user-attachments/assets/6eec6604-27c2-4e9f-90da-d5df7c4801fa)
# Countplot of Vehicle Size
![image](https://github.com/user-attachments/assets/388e03ec-7ca9-418f-935b-aafeb8372c69)
# Grouping on the basis of Make with 'Popularity' values
![image](https://github.com/user-attachments/assets/cbae5a4f-4f78-4cf2-af01-cac2b68b48c2)
# Scatterplot between 'highway MPG' and 'city mpg'
![image](https://github.com/user-attachments/assets/80a2fc3a-b6f9-4bd4-8f64-06b8feefdb55)
# Regplot between 'Engine Cylinders' and 'Engine HP'
![image](https://github.com/user-attachments/assets/cdf6397b-5c75-4683-bdcd-e577f80c4be9)
# Regplot between 'city mpg' and 'Engine Cylinders'
![image](https://github.com/user-attachments/assets/bae869ef-e56f-423f-8566-cc47649c81f1)


# Machine Learning Models & Performance
# Regression plots for model outputs
## Regplot for Decision Tree Regressor
![image](https://github.com/user-attachments/assets/eea2fb85-633f-4dc8-bffd-6795c704b694)
## Regplot of Gradient Boosting Regressor
![image](https://github.com/user-attachments/assets/2c1a0d1c-c602-4579-8701-c763f1bab7a3)
# Barplots comparing model errors
Several regression models were implemented and evaluated on the test data:
![image](https://github.com/user-attachments/assets/1aea1765-a47e-43b4-9fcb-ee1a8c2290cb)
## Barplot of machine learning models with mean absolute error
![image](https://github.com/user-attachments/assets/c9795976-d981-470c-8b9e-ebd4a1966bcb)
## Barplot of machine learning models with mean squared error
![image](https://github.com/user-attachments/assets/b9fccac8-27c3-4c39-ae37-4a9e03e29aa5)
## Bar plot comparing the R² values of different machine learning models to evaluate their predictive performance
![image](https://github.com/user-attachments/assets/63208f06-ec49-4aa4-a656-7863b2bf2765)

# 🧠 Key Learnings
Decision Tree Regressor can effectively predict car prices across a wide range of manufacturers and models.

Bugatti and other luxury brands have distinctly higher prices.

Scatterplots show strong alignment between predicted and actual prices for the best models.

The model generalizes well for both high-priced and lower-priced cars.

# Future Scope
Integrate the best-performing model into a live web application or pricing tool.

Allow users to input features like manufacturer, year, and engine specs to get price predictions in real time.

Expand the dataset with additional car features and recent data to improve model accuracy.

Experiment with ensemble and deep learning models for enhanced predictions.

Incorporate market trends and demand fluctuations for dynamic pricing.

# ✅ Conclusion
This project demonstrates the power of machine learning in predicting car prices using real-world data. Comparing multiple regression models offers insights into model behavior and helps identify the most effective one for this task.
## Recommendation
#### Although some outliers remain in the dataset, it is recommended to perform a thorough outlier detection and removal process. Outliers can negatively impact model accuracy by skewing predictions and increasing error values. Removing or treating these outliers in future iterations may lead to improved model performance and more reliable results.
# 📬 Contact
Farhana Islam
🔗 [LinkedIn](https://www.linkedin.com/in/farhana-islam-261938262)
💻 [GitHub](https://github.com/Farhanaislam1) 

