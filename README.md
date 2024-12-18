# Causal-ML-Thesis-Project
This is a Master thesis project implemented for an international pharmaceutical wholesales company.

Topic: “Cross-Country Analysis of Financial Performance Variation in an International Pharmaceutical Wholesale Company: A Causal Machine Learning Approach”

Goal: It aims to utilize causal machine learning techniques, which combines the power of both statistical techniques and machine learning, to explore the reasons underlying the financial performances differences across countries of a company.

Data Sources: Data is collected from many different sources ranging from public sources from OECD to private sources from the company's SQL server. 

Data Preprocessing: Due to all the different formats, data granuarity, data types, missing values, etc., data preprocessing is immense and of great importance. Specifically, they include the followings.
- Time series projection of the most recent data employing SARIMA
- Missing value interpolation using cubic spline
- Aggregating daily data to monthly data using SQL in SQL server
- Disaggregating quarterly and yearly data to monthly data using cubic spline
- Aligning all data structures and combining them together
- Categorizing data
- Engineering new features
- Tranforming features utilizing one-hot encoding and standardization.

Exploratory Data Analysis (EDA): The following techniques are utilized for understanding the data, detecting outliers and missing values, constructing causal graph, and identifying confounders.
- Correlation analysis
- Univariate analysis
- Bivariate analysis
- PCA analysis
- Feature importance in Random Forest
- Directed acyclic graph (DAG) and backdoor path adjustment 

Implementation of Causal Machine Learning: In particular, the following two techniques are utilized. Underlying machine learning techniques of the two causal machine learning techniques are Random Forest and Lasso Regression.
- Double Machine Learning (DML)
- Causal Forest (CF) with Local Centering

Various robustness checks are performed on the results to ensure their validity.
- Random common cause
- Placebo treatment
- Data subset validation
- Sensitivity analysis

Note: <br />
**Please be noted that as it is a private project within a company, datasets, especially the private ones, are not allowed to be published. Hence, no dataset is attached in this repository. <br />
**Due to the sensitivity of the project, only the insensitive part of the code is attached in this repository and the results are not allowed to be published.
