# Upi_Transactions_Analysis
UPI Transactions Analysis
This repository contains an in-depth analysis of a UPI (Unified Payments Interface) Transactions dataset. The analysis covers various aspects including data cleaning, descriptive statistics, transaction patterns, predictive modeling, anomaly detection, feature importance analysis, and clustering analysis.

# Dataset Description
Overview
This dataset contains simulated data of UPI transactions, which are a popular method of transferring funds between bank accounts in India. UPI allows users to send and receive money using virtual payment addresses (VPAs) linked to their bank accounts.

# Content

1)**Transaction ID**: Unique identifier for each transaction.

2)**Timestamp**: Date and time when the transaction occurred.

3)**Sender Name**: Name of the sender initiating the transaction.

4)**Sender UPI ID**: Virtual Payment Address (VPA) of the sender, including bank identifier (e.g., @okaxis, @oksbi).

5)**Receiver Name**: Name of the recipient receiving the transaction.

6)**Receiver UPI ID**: Virtual Payment Address (VPA) of the receiver, including bank identifier (e.g., @okaxis, @oksbi).

7)**Amount (INR)**: Amount transferred in Indian Rupees (INR) for each transaction.

8)**Status**: Status of the transaction (SUCCESS, FAILED).

# Dataset Size
Total rows: 1000

# Analysis Overview

The analysis is performed in a Jupyter Notebook and includes the following sections:

**Data Overview and Cleaning**: Initial data exploration and cleaning steps.

**Feature Engineering**: Creation of new features such as DayOfWeek and Hour extracted from the Timestamp.

**Descriptive Statistics**: Summary of the dataset’s central tendency, dispersion, and shape.

**Transaction Patterns and Trends**: Visualization of daily transaction counts and amounts.

**Time Series Analysis**: Decomposition of transaction amount time series to observe its trend, seasonality, and residual components.

**Predictive Modeling**: Building a Random Forest Classifier to predict the success or failure of transactions.

**Feature Importance Analysis**: Analysis of the importance of each feature in predicting transaction success using the trained Random Forest model.

**Fraud Detection Analysis**: Examination of transaction amounts by their status and application of Isolation Forest for anomaly detection.

**Clustering Analysis**: Application of PCA for dimensionality reduction and KMeans clustering to segment transactions into different groups.

**Advanced Visualizations**: Creation of a correlation heatmap to visualize the relationships between different features in the dataset.

**Conclusion**: Summary of key insights and suggestions for further analysis.

# Requirements
The following Python libraries are required to run the analysis:

pandas

numpy

matplotlib

seaborn

scikit-learn

statsmodels

You can install the required libraries using pip:

pip install pandas numpy matplotlib seaborn scikit-learn statsmodels

Run the Cells: Execute the cells in the notebook to perform the analysis.

# Conclusion

In this analysis, various techniques are explored to gain insights from the UPI Transactions dataset. The results include identifying daily transaction patterns, building a predictive model for transaction success, detecting anomalies, and clustering transactions into distinct groups. Further analysis could involve more sophisticated models for predictive analytics and deeper investigation into anomalies for fraud prevention.
