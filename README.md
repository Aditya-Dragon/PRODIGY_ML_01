# PRODIGY_ML_01
Task 1 of the internship



# File descriptions
train.csv - the training set
test.csv - the test set
data_description.txt - full description of each column, originally prepared by Dean De Cock but lightly edited to match the column names used here


# House Price Prediction

This project demonstrates a simple house price prediction model using linear regression. The goal is to predict house prices based on specific features, including square footage, the number of bedrooms and bathrooms, and more.

## Getting Started

### Prerequisites

To run the code, you need Python and the following libraries:

- NumPy
- Pandas
- scikit-learn

You can install these libraries using `pip`:

pip install numpy pandas scikit-learn


### Data Loading and Exploration

We load the training and test datasets, explore their structures, and prepare the data for modeling.

### Data Preprocessing

Data preprocessing involves:

- Calculating the total area of each house.
- Selecting relevant features.
- Handling missing values by replacing them with the mean of their respective columns.

### Feature Selection

We use linear regression for modeling and select the following features:

- `TotalArea`: The total area of the house.
- `BedroomAbvGr`: The number of bedrooms above ground.
- `FullBath`: The number of full bathrooms.
- `HalfBath`: The number of half bathrooms.
- `SalePrice`: The Price of the House.

### Training the Model

We split the training data into features (X_train) and the target variable (y_train) and train a linear regression model.

### Making Predictions

We use the trained model to make predictions on the test data.

### Visualizing Predictions

We visualize the distribution of predicted sale prices using a histogram.

## Limitations

The test dataset does not contain the 'SalePrice' column, making it impossible to evaluate model metrics like Mean Absolute Error (MAE), Mean Squared Error (MSE), Root Mean Squared Error (RMSE), and R-squared (R2).

## Acknowledgments

- This project is for educational purposes and serves as an example of linear regression in Python.
- The dataset used for this project can be found on Kaggle.

