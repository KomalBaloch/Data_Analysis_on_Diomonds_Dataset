# **Data Analysis on Diamonds Dataset**  

## **Objectives**

The objective of this project is to analyze the diamonds dataset, including exploring its characteristics, preprocessing the data, and building predictive models for regression (predicting diamond prices). The project aims to:

1. Explore the dataset to understand its structure, distributions, and relationships between features.
2. Preprocess the data by handling missing values, label encoding, and scaling features if necessary.
3. Conduct hypothesis testing to identify relationships between features and the target variable (price).
4. Build multiple regression models to predict diamond prices based on their characteristics.
5. Evaluate the performance of regression models using appropriate metrics like Root Mean Squared Error (RMSE).
6. Select the best regression model based on evaluation metrics.
7. Provide insights and recommendations based on model results and analysis.

## **Dataset Overview**

The diamonds dataset contains the following fields:

- `carat`: The weight of the diamond, measured in carats.
- `cut`: Quality of the cut, categorized as Fair, Good, Very Good, Premium, or Ideal.
- `color`: Color of the diamond, ranging from J (worst) to D (best).
- `clarity`: Clarity of the diamond, ranging from I1 (worst) to IF (best).
- `depth`: The height of a diamond, measured from the culet to the table, divided by its average girdle diameter.
- `table`: The width of the diamond's table (the flat top facet) expressed as a percentage of its average diameter.
- `price`: Price of the diamond in US dollars.
- `x`: Length of the diamond in mm.
- `y`: Width of the diamond in mm.
- `z`: Depth of the diamond in mm.

## **Project Structure**

- **Data Preprocessing**: Handle missing values and encode categorical variables.
- **Exploratory Data Analysis (EDA)**: Visualize distributions and relationships using Seaborn and Matplotlib.
- **Hypothesis Testing**: Identify relationships between key features and the target variable (price).
- **Modeling**: Train and evaluate multiple regression models, including Linear Regression, Ridge, Lasso, Decision Trees, Random Forest, and Gradient Boosting.
- **Model Evaluation**: Evaluate models using RMSE and select the best model.
- **Save Model**: Use Pickle to save the trained models.

## **Technologies and Libraries Used**

- **Languages**: Python
- **Libraries**:
  - Pandas
  - NumPy
  - Matplotlib
  - Seaborn
  - Scikit-learn
  - Pickle
