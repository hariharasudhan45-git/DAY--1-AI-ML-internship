# Titanic Data Cleaning & Preprocessing

Welcome to this mini project where we clean and prepare the Titanic dataset for machine learning tasks!

This project focuses on the **essential data preprocessing steps** every ML pipeline needs — handling missing values, encoding categories, normalizing features, and removing outliers.

## Objective
To clean and preprocess raw Titanic data so it's ready for training ML models.

## Tools Used
- Python
- Pandas
- NumPy
- Seaborn & Matplotlib (for visualizations)
- Scikit-learn (for standardization)

## Steps Followed
1. **Load & Explore the Dataset**
   - Checked data types, null values, and got a feel for the dataset.

2. **Handle Missing Values**
   - Dropped the `Cabin` column (too many missing).
   - Filled `Age` with the median.
   - Filled `Embarked` with the mode.

3. **Encode Categorical Variables**
   - Converted `Sex` and `Embarked` using `pd.get_dummies()`.

4. **Normalize Numerical Features**
   - Standardized `Age` and `Fare` using `StandardScaler`.

5. **Visualize & Remove Outliers**
   - Plotted boxplots.
   - Removed outliers using the IQR method.

## Final Output
A clean dataset, free of missing values and outliers, with all numerical and categorical features properly prepared.

## How to Use
1. Clone the repo.
2. Run the `.py` or `.ipynb` file with the dataset in the same directory.
3. You’re ready to build models!
