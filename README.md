# Titanic Data Cleaning & Exploratory Data Analysis

------------------------------------------------------------

# ✅ Task 1: Data Cleaning & Preprocessing

## 🎯 Objective
To prepare raw data for Machine Learning by handling missing values, encoding categorical variables, and detecting outliers.

## 🔹 Steps Performed

1. Imported necessary libraries (Pandas, NumPy, Matplotlib, Seaborn, Sklearn).
2. Loaded the Titanic dataset.
3. Checked dataset structure using:
   - info()
   - describe()
   - isnull().sum()

4. Handled Missing Values:
   - Filled Age with median.
   - Filled Embarked with mode.
   - Dropped Cabin column due to excessive missing values.

5. Converted Categorical Variables:
   - Converted Sex into numerical format (male/female).
   - Applied encoding where necessary.

6. Feature Scaling:
   - Standardized numerical features like Age and Fare.

7. Outlier Detection:
   - Used boxplots.
   - Applied IQR method for identifying extreme values.

## 📊 Outcome
A cleaned and preprocessed dataset ready for Machine Learning model building.

------------------------------------------------------------

# ✅ Task 2: Exploratory Data Analysis (EDA)

## 🎯 Objective
To understand the dataset using statistical analysis and visualizations.

## 🔹 Steps Performed

1. Generated summary statistics:
   - Mean
   - Median
   - Standard deviation
   - Skewness

2. Visualized numerical features using:
   - Histograms
   - Boxplots

3. Analyzed categorical variables:
   - Survival distribution
   - Survival by Gender
   - Survival by Passenger Class

4. Created correlation matrix to understand relationships between features.

5. Used pairplot to visualize feature interactions.

6. Identified patterns and trends from visualizations.

------------------------------------------------------------

# 🔍 Key Insights

- Female passengers had a higher survival rate compared to males.
- Passengers in 1st class were more likely to survive.
- Fare distribution is highly right-skewed.
- Outliers are present in Fare column.
- Passenger class and fare are strongly related.

------------------------------------------------------------

# 🛠 Tools Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- Plotly


------------------------------------------------------------


