# Car-Price-Prediction-Using-Machine-Learning
This project aims to analyze the factors influencing car prices in the American market and build machine learning models to predict car prices based on these factors. A Chinese automobile company is looking to enter the US market, and this analysis will guide them in designing cars and setting competitive prices.

Problem Statement
The company wants to understand:

Which factors significantly affect car pricing.
How well these factors predict car prices.
Using a dataset of cars in the American market, this project builds and evaluates regression models to predict car prices and identify key variables influencing these prices.

Goals
Build regression models to predict car prices.
Identify the most important features affecting pricing.
Provide insights for business strategy and product design.
Dataset
The dataset contains detailed information on various car models, including their specifications and prices. Categorical features are one-hot encoded, and numerical features are standardized for better model performance.

Key Components
1. Data Preprocessing
Handled missing values, encoded categorical variables, and standardized numerical features.
2. Model Implementation
Implemented the following regression algorithms:

Linear Regression
Decision Tree Regressor
Random Forest Regressor
Gradient Boosting Regressor
Support Vector Regressor
3. Model Evaluation
Models were evaluated based on:

R-squared (R²): Measures model fit.
Mean Squared Error (MSE): Quantifies average squared difference between predicted and actual values.
Mean Absolute Error (MAE): Measures average magnitude of errors.
4. Feature Importance Analysis
Identified significant variables influencing car prices using feature importance scores from tree-based models.

5. Hyperparameter Tuning
Improved model performance through hyperparameter optimization.

Results
The best-performing model was identified based on evaluation metrics.
Key insights into the most significant factors affecting car prices were derived.
Technologies Used
Python
Libraries: Pandas, NumPy, Scikit-learn, Matplotlib, Seaborn

Key Insights
Feature importance analysis reveals which car features are most valued in the American market.
The models provide a framework for setting competitive car prices.
Conclusion
This project showcases the use of machine learning techniques to solve a real-world business problem, helping a company design products and set pricing strategies for a new market.







