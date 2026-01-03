# ML-Project-D-
# DS230-Instacart-Project
## Team Members
- Dania ALsebaie
- Douha ALjedaih
 
# Dania ALsebaie
-Exploratory Data Analysis (EDA) with visualizations
-Outlier detection & treatment
-Define and justify imputation techniques for missing fields
-Dimensionality & collinearity Identify multicollinearity (VIF) and either remove or regularize features
-Imbalanced Data Handling: Applied class weights and sampling strategies (SMOTE) to address classification bias


************************************************************************************************************************************************************************


# Douha ALjedaih
-Exploratory Data Analysis (EDA) with visualizations
-Feature Engineering: Developed user-level, product-level, and interaction features from shopping history
-Encoding Categorical Variables: Implemented multiple encoding strategies (One-Hot and Target Encoding) 
-Feature Scaling: Applied appropriate scaling techniques (StandardScaler/MinMax) based 

## Code Location
All project code is provided in the following Jupyter Notebook:
- ml-final-project-d.ipynb

The notebook was developed and executed on Kaggle.
## Work Completed
The main focus of this project was on data preprocessing and feature
engineering, including:

- Merging multiple Instacart tables
-  Exploratory Data Analysis (EDA) with visualizations
- Feature engineering at user and product levels
-  Data cleaning and handling missing values
- Encoding Categorical Variables
- Imbalanced Data Handling: Applied class weights and sampling strategies (SMOTE) to address classification bias.
## Challenges and Limitations
While working on the project, we encountered an issue with data leakage and had difficulty implementing a correct time-aware data split. Due to the dataset structure, we were unsure how to split the data strictly by time without introducing leakage We tried using the order_number for time-based splitting but it was later removed after calculating VIF
