# Titanic Dataset - Data Cleaning & Preprocessing

## Objective

The objective of this project is to clean and preprocess the Titanic dataset and prepare it for machine learning applications.

## Dataset

The Titanic dataset contains information about passengers, including age, gender, ticket fare, passenger class, and survival status.

## Tools and Libraries Used

* Python
* Pandas
* NumPy
* Matplotlib
* Seaborn
* Scikit-learn

## Steps Performed

### 1. Data Loading

Loaded the Titanic dataset using Pandas.

### 2. Data Exploration

* Checked dataset shape.
* Examined data types.
* Identified missing values.

### 3. Missing Value Handling

* Filled missing values in the Age column using the median.
* Filled missing values in the Embarked column using the mode.

### 4. Data Cleaning

* Removed unnecessary columns:

  * Cabin
  * Name
  * Ticket

### 5. Encoding Categorical Variables

Applied Label Encoding to:

* Sex
* Embarked

### 6. Feature Scaling

Standardized numerical features:

* Age
* Fare

### 7. Outlier Detection

Visualized outliers in the Fare column using a boxplot.

## Output

Generated a cleaned dataset named:

cleaned_titanic.csv

## Files Included

* Titanic-Dataset.csv
* cleaned_titanic.csv
* task1.ipynb
* README.md

## Conclusion

The Titanic dataset was successfully cleaned and preprocessed. Missing values were handled, categorical variables were encoded, numerical features were scaled, and the final cleaned dataset was prepared for further analysis and machine learning tasks.
