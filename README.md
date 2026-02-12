# Data Cleaning & Preprocessing - Titanic Dataset

## What I Did
This is my first task for the AI & ML Internship. I cleaned and prepared the Titanic dataset for machine learning.

## Dataset
- **Name:** Titanic Dataset
- **Size:** 891 passengers, 12 columns
- **Target:** Predict survival (Survived column)

## Steps I Followed

### 1. Loaded the Data
- Used pandas to read the CSV file
- Checked the first few rows with `df.head()`

### 2. Handled Missing Values
- **Age:** Filled missing values with median age
- **Embarked:** Filled missing values with the most common port
- **Cabin:** Dropped this column (too many missing values)

### 3. Removed Unnecessary Columns
- Dropped **Name** and **Ticket** columns (not useful for prediction)

### 4. Encoded Categorical Data
- **Sex:** Converted male/female to 1/0 (Label Encoding)
- **Embarked:** Created separate columns for each port (One-Hot Encoding)

### 5. Handled Outliers
- Created boxplots to see outliers
- Used IQR method to clip extreme values in Age, SibSp, Parch, and Fare

### 6. Scaled the Data
- Applied StandardScaler to make all numbers on the same scale
- This helps machine learning models work better

## Tools Used
- **Python 3**
- **pandas** - for data manipulation
- **numpy** - for numerical operations
- **matplotlib & seaborn** - for visualizations
- **sklearn** - for scaling and preprocessing

## Files in This Repo
- `Data_Cleaning___Preprocessing.ipynb` - Main notebook with all the code
- `README.md` - This file

## What I Learned
- How to handle missing data properly
- Different ways to encode categorical variables
- How to detect and remove outliers
- Why feature scaling is important for ML

## How to Run
1. Clone this repository
2. Make sure you have pandas, numpy, matplotlib, seaborn, and sklearn installed
3. Open the notebook in Jupyter
4. Run all cells

---

**Task Completed:** ✅  
**Submitted for:** AI & ML Internship - Task 1
