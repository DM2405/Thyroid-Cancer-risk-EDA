# Thyroid Cancer Risk Analysis – Exploratory Data Analysis (EDA)

## Project Overview
This project performs an in-depth Exploratory Data Analysis (EDA) on a Thyroid Cancer Risk dataset to understand how demographic and medical factors influence the likelihood of thyroid cancer. The analysis includes data cleaning, univariate, bivariate, and advanced visualizations with clear interpretations.


## Dataset Description
The dataset contains patient-level information including:
- Demographic attributes (Age, Gender, etc.)
- Medical indicators
- Thyroid cancer diagnosis (target variable)
The goal is to explore patterns, relationships, and risk factors associated with thyroid cancer.


## Data Cleaning Steps
- Checked and handled missing values
- Removed duplicate records
- Corrected data types
- Encoded categorical variables for correlation analysis
- Preserved medically meaningful outliers


## Exploratory Data Analysis (EDA)

### Univariate Analysis
- Target variable distribution
- Age distribution
- Gender distribution
- Outlier detection using boxplots

### Bivariate Analysis
- Age vs Cancer Risk
- Gender vs Cancer Risk
- Numerical features vs Target
- Categorical features vs Target

### Advanced Analysis
- KDE plots
- Violin plots
- Scatter plots with interactions
- Correlation heatmaps
Each visualization includes a concise interpretation explaining how the feature affects thyroid cancer risk.


## Key Insights
- Thyroid cancer cases are more prevalent in older age groups
- Gender shows noticeable differences in cancer occurrence
- Certain medical indicators show higher values among cancer patients
- Cancer risk is influenced by a combination of multiple factors rather than a single feature
- Dataset shows class imbalance, which is important for predictive modeling


## Conclusion
The analysis reveals that thyroid cancer risk in this dataset is strongly influenced by age, demographic characteristics, and abnormal medical indicators. While no single feature can fully predict cancer, combined feature interactions provide meaningful predictive power, making this dataset suitable for machine learning classification models.


## Future Work
- Feature scaling and selection
- Machine learning models (Logistic Regression, Random Forest, XGBoost)
- Feature importance analysis
- Model evaluation using ROC-AUC, confusion matrix


## Tools & Libraries
- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
