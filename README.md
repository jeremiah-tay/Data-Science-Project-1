# Data-Science-Project-1

This is a **data science project** that outlines the process of building and evaluating machine learning models for predicting median house values using **Python and scikit-learn.**

1. **Importing Libraries:** Necessary libraries such as Pandas, NumPy, Matplotlib, Seaborn, and scikit-learn modules are imported to facilitate data handling, visualization, and modeling.

2. **Data Loading and Preprocessing:** The housing dataset is loaded from a CSV file. Missing values are dropped, and the features (X) and target variable (y) are separated. The dataset is then split into training and testing sets using the train_test_split function.

3. **Feature Engineering:** Various feature engineering techniques are applied to the training data. Histograms of features are visualized to understand their distributions. Certain features are log-transformed, and new features such as bedroom ratio and household rooms are created.

4. **Data Scaling:** The training data is standardized using StandardScaler to ensure that all features have the same scale, which can improve the performance of certain machine learning algorithms.

5. **Model Training and Evaluation (Linear Regression):** A Linear Regression model is initialized, fitted to the scaled training data, and evaluated using the testing data. The model's performance is assessed using the R-squared score.

6. **Model Training and Evaluation (Random Forest):** A Random Forest Regressor model is initialized, fitted to the scaled training data, and evaluated using the testing data. The model's performance is assessed using the R-squared score.

7. **Hyperparameter Tuning (Random Forest):** Hyperparameters of the Random Forest model are tuned using Grid Search Cross-Validation (GridSearchCV). Different combinations of hyperparameters are tested to find the best-performing model.


This code demonstrates a structured approach to building and evaluating machine learning models for predicting median house values, starting from data preprocessing to model selection and evaluation. 
It also showcases the importance of hyperparameter tuning to optimize model performance.




