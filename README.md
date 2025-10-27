link# 📊 Telco Customer Segmentation using Clustering

This project is a **data science case study** focused on segmenting customers from the **Telco Customer Churn dataset** using various **clustering techniques**.
The aim is to uncover meaningful customer groups based on demographics, service usage, and billing patterns — providing insights for targeted marketing and churn prevention.

---

## 🧩 Project Overview

Customer churn is a major challenge in the telecom industry. By applying **unsupervised learning**, we can identify distinct customer segments that help the company understand customer behavior and improve retention strategies.

In this case study, I performed **Exploratory Data Analysis (EDA)**, **data preprocessing**, and applied multiple clustering algorithms to discover patterns and hidden structures in the data.

---

## 📁 Dataset

**Dataset name:** Telco Customer Churn Dataset
**Source:** Public dataset available on [Kaggle](https://www.kaggle.com/blastchar/telco-customer-churn)

**Features include:**

* **Demographics:** `gender`, `SeniorCitizen`, `Partner`, `Dependents`
* **Services:** `PhoneService`, `MultipleLines`, `InternetService`, `OnlineSecurity`, `StreamingTV`, etc.
* **Account Information:** `Contract`, `PaymentMethod`, `PaperlessBilling`, `tenure`, `MonthlyCharges`, `TotalCharges`
* **Target Variable (for reference):** `Churn`

---

## 🎯 Objective

The main goal of this project is to:

* Perform **clustering analysis** to group customers with similar characteristics.
* Identify **key behavioral patterns** among churned and non-churned customers.
* Provide **actionable insights** for business decisions.

---

## 🔍 Methodology

### 1. Data Preprocessing

* Handled missing and inconsistent values (e.g., `TotalCharges` column).
* Converted categorical variables using **Label Encoding** / **One-Hot Encoding**.
* Scaled numerical features using **StandardScaler**.

### 2. Exploratory Data Analysis (EDA)

* Visualized distributions of key numerical and categorical features.
* Examined relationships between churn and customer attributes.
* Checked correlations and multicollinearity.

### 3. Clustering Techniques

Applied and compared multiple clustering algorithms:

* **K-Means Clustering**
* **Hierarchical Clustering**
* (Optional) **DBSCAN** for density-based segmentation

### 4. Optimal Cluster Selection

* Used **Elbow Method** and **Silhouette Score** to determine the best number of clusters.

### 5. Visualization

* Reduced dimensions using **PCA (Principal Component Analysis)** for cluster visualization.
* Created insightful plots to interpret each cluster’s characteristics.

---

## 🧠 Key Insights

* Customers with **month-to-month contracts** and **electronic payment methods** were more likely to churn.
* Clusters revealed groups of **high-paying long-term customers** vs **low-tenure, high-risk customers**.
* Internet service type and contract duration were strong indicators of customer stability.

---

## 🧰 Tools and Libraries

* **Python 3.x**
* **Pandas**, **NumPy** — data cleaning & manipulation
* **Matplotlib**, **Seaborn** — visualizations
* **Scikit-learn** — clustering algorithms & preprocessing
* **PCA** — dimensionality reduction

---

## 🚀 How to Run the Project

1. Clone this repository:

   ```bash
   git clone https://github.com/<your-username>/telco-clustering-case-study.git
   ```

2. Navigate into the folder:

   ```bash
   cd telco-clustering-case-study
   ```

3. Install dependencies:

   ```bash
   pip install -r requirements.txt
   ```

4. Open the Jupyter Notebook:

   ```bash
   jupyter notebook clustering__case_study.ipynb
   ```

---

## 📈 Results

The project successfully segmented customers into **meaningful clusters** that reflect behavioral differences and potential churn risk levels.
These insights can support **marketing**, **customer retention**, and **service personalization** strategies.

---

## ✍️ Author

**Junaid Solangi**
*M.Phil Data Science Candidate | Data Analyst | Machine Learning Enthusiast*
📧 jun41d48hmad@gmail.com
💼 www.linkedin.com/in/junaid-solangi-7b439b24a
