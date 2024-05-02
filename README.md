This breast cancer machine learning project utilizes a dataset comprising 569 rows and 32 columns.
The dataset is devoid of any null values.

Exploratory Data Analysis (EDA):

The analysis reveals a predominance of benign cases over malignant cases. 
Density graphs were plotted to visualize the distribution.

Feature Engineering:

To address multicollinearity issues, highly correlated features were removed, resulting in 24 remaining columns. Additionally, outlier detection was performed, revealing the presence of outliers in most columns.

Data Preprocessing:

The dataset was split into training and testing sets. Data scaling was applied to ensure uniformity across features.

Model Building and Evaluation:

Several classification models including Logistic Regression, K-Nearest Neighbors (KNN), Decision Trees, Random Forest, and Support Vector Machine (SVM) were trained and tested. The SVM model achieved the highest accuracy of 96.4%.

This project provides a comprehensive approach to breast cancer classification, offering valuable insights and predictive accuracy
