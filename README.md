# Project2-EV
**Problem Statement:**
The objective of this project is to perform in-depth customer segmentation analysis using electric vehicle (EV) usage data. By segmenting customers based on their EV usage patterns, we aim to assist an EV company in tailoring their marketing strategies and product offerings to specific customer segments. This analysis will enable the company to target the right customer groups effectively, thereby maximizing their marketing efforts and sales potential.

**Size:**
9 Columns and 500 Rows

	customer_id,	Age,	Income,	Occupation,	Location,	Electric_vehicle_ownership,	Vehicle_type_Preference,	Charging,	Environment_consiousness.

**Process:**
I Perform my coding task in google colab and i use google-drive to create links

**Data Cleaning & and getting insights:**

Conducted thorough data cleaning, including handling missing values, duplicates, and outliers.
Utilized descriptive statistics and visualizations to gain insights into the distribution and characteristics of the data.
Identified key features that could potentially influence customer segmentation.

**Feature Encoding:**

Applied label encoding to categorical variables to convert them into numerical format for machine learning algorithms.
Ensured consistency in data representation to facilitate model training.

**Feature Scaling:**

Performed feature scaling using min-max scaling to normalize feature values within a specified range.
Addressed potential biases in the data caused by varying feature scales.


**K-means Clustering:**

Applied the k-means clustering algorithm to group customers into distinct segments based on their EV usage patterns.
Clustered customers into five distinct groups to facilitate targeted marketing strategies.

**Creation of Grouping Result Dataframe:**

Generated a dataframe containing the customer IDs and their respective cluster assignments.
Provided a structured format for further analysis and interpretation of clustering results.
Libraries Used:
Pandas
Matplotlib
Seaborn
Scikit-learn

# Dataset:
Link to Dataset:[ click here](https://drive.google.com/file/d/1bEcWGFGad-2wltwUKco5nvruS9eSfMil/view?usp=drive_link)
