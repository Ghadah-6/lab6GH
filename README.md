# lab6GH
This lab focused on cleaning and preparing data before building machine learning models using the USA Housing Dataset.

Task 1: Data Quality Assessment
No missing values or duplicates found

All numerical columns are correctly formatted

Identified potential outliers in the 'Price' column

Task 2: Missing Values (Median Imputation)
Introduced artificial missing values for practice

Chose Median Imputation because housing prices are right-skewed

Median is robust to outliers and preserves dataset size

Task 3: Outlier Handling (IQR Method)
Used IQR = Q3 - Q1 to detect outliers

Detected ~5% outliers in Price column

Chose Capping (5th/95th percentiles) instead of removal

Preserves extreme but valid values

Task 4: Normalization
Method	Range
Min-Max	[0, 1]
Z-Score	Mean=0, Std=1
Task 5: PCA
Found strong correlations (Rooms vs Bedrooms: ~0.70)

PCA recommended - 2 components explained ~70% of variance
