# Customer-Purchasing-Behavior-Analysis_Finished

This repository contains an end-to-end unsupervised machine learning project to analyze and segment customers based on their demographics and purchasing behavior. 
By leveraging clustering techniques, we aim to uncover hidden patterns and customer groups that can inform targeted marketing strategies.

---

### A. Objective
The objective is to segment customers using `KMeans Clustering`, based on features such as age group, income level, spending habits, and product engagement. The resulting clusters help identify distinct customer personas for data-driven marketing decisions, retention strategies, and personalization.

---

### B. Dataset Information
- The file name is `marketing_campaign.csv`.
- Original source is from https://www.kaggle.com/datasets/imakash3011/customer-personality-analysis.
- Loaded from GitHub via https://raw.githubusercontent.com/yohaneskh/Customer-Purchasing-Behavior-Analysis_Finished/refs/heads/main/marketing_campaign.csv.

---

### C. Workflow Overview
1. Importing Libraries
- Essential Python packages were imported for analysis, visualization, and modeling.

2. Loading and Inspecting the Dataset
- Loaded the raw dataset.
- Explored general structure, null values, and column descriptions.

3. Data Cleaning & Feature Engineering.
- Engineered new features into bins like `Age_Group`.
- Replace missing values of `Income` variable with median value, and remove missing values from `Age_Group` variable.
- Applied `Winsorization` to limit the impact of extreme outliers.

4. Preprocessing.
- Scaled numerical features using `StandardScaler`.
- Encoded categorical features using `LabelEncoder`.

5. Clustering.
- Used `KMeans` for customer segmentation.
- Determined optimal number of clusters using `Elbow Method`.
- Applied `PCA` to visualize clusters in 2D space.

6. Cluster Evaluation.
- Interpreted clusters based on purchasing patterns, campaign response, product preferences, and age groups.
- Compared cluster distribution using bar plots and cross-tab analysis.

---

### D. Insights & Use Cases
- Clear segmentation of customer personas based on age group, product categories, and purchasing channels.
- Customers demonstrated consistent high spending across product categories, useful for upselling.

---

### E. Dependencies
Main Python packages used in this project are as following:
- `pandas`
- `numpy`
- `matplotlib`
- `seaborn`
- `scikit-learn`

---

## Author
Yohanes Kurniawan Hertanto

An aspiring Data Analyst with interest in Machine Learning

https://www.kaggle.com/yohaneskhyekaha
