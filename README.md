# Multiple Linear Regression

This code demonstrates how to perform Multiple Linear Regression using the scikit-learn library in Python.

## Dataset

The dataset used in this code is the '50_Startups.csv' file, which contains information about 50 startup companies, including their R&D spend, administration spend, marketing spend, state, and profit.

## Libraries

The following libraries are imported:

- `numpy` for numerical operations
- `matplotlib.pyplot` for data visualization
- `pandas` for data manipulation and analysis
- `sklearn.compose` for data transformation
- `sklearn.preprocessing` for encoding categorical data
- `sklearn.model_selection` for splitting the dataset
- `sklearn.linear_model` for building the linear regression model

## Steps

1. Import the necessary libraries.
2. Import the dataset using `pd.read_csv('50_Startups.csv')`.
3. Separate the independent variables (X) and the dependent variable (y) from the dataset.
4. Encode the categorical data (in this case, the 'State' column) using `OneHotEncoder`.
5. Split the dataset into training and test sets using `train_test_split`.
6. Train the Multiple Linear Regression model on the training set using `LinearRegression`.
7. Use the trained model to make predictions on the test set.
8. Compare the predicted values with the actual values from the test set.

## Usage

To run this code, you need to have the '50_Startups.csv' file in the same directory as your Python script. Additionally, make sure you have the required libraries installed (`numpy`, `matplotlib`, `pandas`, and `scikit-learn`).

After running the code, it will print the predictions made by the Multiple Linear Regression model on the test set, along with the actual values from the test set.

## Note

The code provided assumes that you have a basic understanding of Python programming and machine learning concepts. If you encounter any issues or have further questions, feel free to consult the documentation or seek assistance from online resources or communities.
