
# Property Price Predictor


This is a model for predicting property prices based on various features. The script includes data loading, cleaning, feature engineering, outlier removal, and the building of a machine learning model. The primary model used is Linear Regression, and cross-validation is employed to assess its accuracy.

### Prerequisites

- Python (3.x recommended)
- scikit-learn
- NumPy
- Matplotlib
- Seaborn


### Steo Included

- Data Loading
Load Banglore home prices into a dataframe.

- Data Exploration
Explore the dataset's shape and columns.

- Feature Selection
Drop features that are not required for building the model.

- Data Cleaning
    1. Handle missing values.

- Feature Engineering
Add a new feature for the number of bedrooms (bhk).

- Data Preprocessing
Handle irregularities in the 'total_sqft' feature.

- Feature Engineering
Add a new feature called "price per square feet."

- Exploratory Data Analysis
Examine the distribution of 'price_per_sqft' feature.

- Dimensionality Reduction
Apply dimensionality reduction techniques to the 'location' feature.

- Outlier Removal
    1. Remove outliers based on business logic.
    2. Outlier Removal Using Standard Deviation and Mean
    3. Remove outliers based on standard deviation and mean.


- One Hot Encoding For Location
Use one-hot encoding for the 'location' feature.

- Data Preprocessing
Drop the 'location' feature.

- Model Building
Prepare the data for training and testing.

- Linear Regression Model
    1. Train a Linear Regression model and assess its accuracy.
    2. Use K Fold cross-validation to measure the accuracy of the Linear Regression model.
