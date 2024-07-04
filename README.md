# PRODIGY_ML_01
House Price Prediction Using Linear Regression This project implements a linear regression model to predict house prices based on square footage, number of bedrooms, and number of bathrooms.

Dataset The dataset used in this project should contain the following columns:

Square_Footage: Total square footage of the house Bedrooms: Number of bedrooms Bathrooms: Number of bathrooms Price: Price of the house Ensure that the dataset is structured with these features and target variable (Price). The dataset should be preprocessed and cleaned before training the model.

Implementation Steps Data Loading: Load the dataset containing house data (CSV file, database, etc.).

Data Preparation:

Check for missing values and handle them appropriately (imputation, removal, etc.). Ensure all numerical features are in a suitable format for modeling. Exploratory Data Analysis (EDA):

Visualize the relationships between each feature (square footage, bedrooms, bathrooms) and the target variable (house prices) using scatter plots or other appropriate visualizations. Feature Selection:

Determine which features (square footage, bedrooms, bathrooms) to include in the model based on EDA and domain knowledge. Model Training:

Split the dataset into training and testing sets (e.g., 80% training, 20% testing). Instantiate a linear regression model using libraries such as scikit-learn. Train the model using the training data. Model Evaluation:

Evaluate the performance of the trained model using appropriate metrics such as Mean Squared Error (MSE), R-squared (R²), and others. Interpret the model coefficients to understand the impact of each feature on the house prices. Prediction:

Use the trained model to make predictions on new data or test data. Validate the predictions against the actual prices to assess the model's accuracy.
