# 🏡 House Prices - Advanced Regression Techniques

This project is a solution to the Kaggle competition: [House Prices - Advanced Regression Techniques](https://www.kaggle.com/competitions/house-prices-advanced-regression-techniques).

The goal is to predict the final price of homes based on various features provided in the dataset.

## 📁 Dataset

- Source: Kaggle
- Files:
  - `train.csv`: training data with features and target (`SalePrice`)
  - `test.csv`: test data without target values
  - `sample_submission.csv`: format for Kaggle submission

## 🔍 Workflow

### 1. Exploratory Data Analysis (EDA)
- Used `.describe()`, `.info()`, and `.corr()` to understand the dataset
- Visualized distributions and outliers
- Identified missing values and skewed features

### 2. Data Cleaning & Preprocessing
- Handled missing data
- Applied one-hot encoding for categorical features
- Transformed skewed numerical features using `log1p`

### 3. Modeling
- Used **Linear Regression** (or any model you used)
- Trained on processed data
- Evaluated using RMSE and cross-validation

### 4. Submission
- Created predictions on the test set
- Submitted results in Kaggle submission format

## 🛠 Technologies Used
- Python
- Pandas, NumPy, Matplotlib, Seaborn
- Scikit-learn

## 📊 Evaluation
- Primary metric: Root Mean Squared Error (RMSE)
- (Include your score if you have it)

## 💡 Future Improvements
- Try advanced models like XGBoost or LightGBM
- Hyperparameter tuning
- Feature selection/engineering

---

Made with ❤️ by Omar Ahmed
