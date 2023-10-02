# Housing-prices-prediction-model


Project Name: Housing Prices Prediction Model

**Description:**

This project is aimed at creating a predictive model for housing prices using machine learning techniques. The project utilizes the Python programming language and several popular libraries for data analysis and machine learning, including Pandas, NumPy, Matplotlib, Seaborn, and Scikit-Learn.

**Project Steps and Highlights:**

1. **Data Import and Inspection:**
   - The project starts by importing the dataset from a CSV file ("housing.csv") using Pandas.
   - An initial exploration of the dataset is performed, displaying the first few rows and summary statistics of the data.

2. **Data Preprocessing:**
   - Missing data is handled by removing rows with missing values using the `data.dropna(inplace=True)` method.
   - Data visualization is employed to understand the data better, including histograms to visualize the distribution of numerical attributes and a heatmap to visualize the correlations between attributes.

3. **Feature Engineering:**
   - Several feature engineering techniques are applied to enhance the dataset for modeling.
   - Logarithmic transformations are performed on specific attributes like "total_rooms," "total_bedrooms," "population," and "households" to improve their distribution and relationship with the target variable.

4. **One-Hot Encoding:**
   - The categorical attribute "ocean_proximity" is converted into a numerical format using one-hot encoding.

5. **Machine Learning Model Building:**
   - Linear Regression and Random Forest Regressor models are employed for predicting housing prices.
   - Standardization is applied to the feature variables using Scikit-Learn's `StandardScaler`.

6. **Model Evaluation:**
   - The models' performance is evaluated using the coefficient of determination (R-squared) score.
   - The Random Forest Regressor outperforms the Linear Regression model, with a higher R-squared score.

7. **Hyperparameter Tuning:**
   - A grid search is performed to optimize the hyperparameters of the Random Forest Regressor using GridSearchCV.
   - The best estimator from the grid search is used to predict housing prices, resulting in improved model performance.

**Conclusion:**

This project demonstrates the process of developing a predictive model for housing prices using machine learning techniques. It includes data preprocessing, feature engineering, model building, and hyperparameter tuning to optimize model performance. The Random Forest Regressor is found to be the better-performing model for predicting housing prices in this context.

You can refer to the code and visualizations provided in the master branch of the project to understand the details of the data analysis and modeling process.
