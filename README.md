# 📊 Telecom Customer Churn Data Analysis Using Python (EDA)

## 📌 Project Overview

This project focuses on performing **Exploratory Data Analysis (EDA)** on a Telecom Customer Churn dataset using Python. The goal is to identify the major factors affecting customer churn and extract actionable business insights.

The analysis includes:

* Data cleaning and preprocessing
* Exploratory data analysis (EDA)
* Data visualization
* Customer behavior analysis
* Churn pattern identification

This project helps understand why customers leave telecom services and which customer groups are more likely to churn.

---

# 📂 Project Structure

```bash
Telecom-Customer-Churn-Analysis/
│
├── Telecom Customer Chrun Data Analysis Using Python (EDA).ipynb
├── Customer Churn.csv
├── README.md
```

---

# 🛠️ Technologies Used

* Python
* Pandas
* NumPy
* Matplotlib
* Seaborn
* Jupyter Notebook

---

# 📁 Dataset Information

The dataset contains customer information such as:

* Customer demographics
* Contract details
* Internet services
* Payment methods
* Monthly and total charges
* Churn status

Dataset size:

* **Rows:** 7043
* **Columns:** 21

---

# 🧹 Data Cleaning & Preprocessing

The following preprocessing steps were performed:

* Replaced blank values in `TotalCharges`
* Converted `TotalCharges` datatype from object to float
* Checked for null values
* Checked duplicate customer IDs
* Converted `SeniorCitizen` values from `0/1` to `Yes/No`

Example:

```python
df["TotalCharges"] = df["TotalCharges"].replace(" ","0")
df["TotalCharges"] = df["TotalCharges"].astype("float")
```

---

# 📊 Exploratory Data Analysis (EDA)

## 1️⃣ Customer Churn Distribution

* Total churned customers analyzed
* Churn percentage visualization using pie charts

### Key Insight:

* Around **26.54% customers have churned**. 

---

## 2️⃣ Gender-Based Churn Analysis

* Compared churn rate between male and female customers

### Key Insight:

* Churn behavior is almost similar across genders.

---

## 3️⃣ Senior Citizen Analysis

* Analyzed churn rate among senior citizens

### Key Insight:

* Senior citizens show a comparatively higher churn percentage. 

---

## 4️⃣ Tenure Analysis

* Analyzed customer retention based on service duration

### Key Insight:

* Customers with very low tenure (1–2 months) are more likely to churn.
* Long-term customers tend to stay. 

---

## 5️⃣ Contract Type Analysis

* Compared churn across:

  * Month-to-month
  * One-year
  * Two-year contracts

### Key Insight:

* Customers with month-to-month contracts are more likely to churn. 

---

## 6️⃣ Services Analysis

Services analyzed:

* Phone Service
* Internet Service
* Online Security
* Tech Support
* Streaming Services
* Device Protection

### Key Insight:

* Customers without additional security and support services show higher churn rates. 

---

## 7️⃣ Payment Method Analysis

* Compared churn rate across payment methods

### Key Insight:

* Customers using **Electronic Check** are more likely to churn. 

---

# 📈 Visualizations Used

* Count Plots
* Pie Charts
* Histograms
* Stacked Bar Charts
* Multi-variable categorical plots

---

# 🎯 Key Business Insights

* Month-to-month contract customers are at higher churn risk.
* Senior citizens churn more frequently.
* Customers using electronic check payment methods churn more.
* Customers with longer tenure are more loyal.
* Additional support services improve customer retention.

---

# 🚀 Future Improvements

* Build a machine learning churn prediction model
* Deploy churn prediction dashboard
* Use Power BI/Tableau for interactive dashboards
* Perform feature engineering
* Implement customer segmentation

---

# 📚 Learning Outcomes

Through this project, I learned:

* Real-world data cleaning techniques
* Exploratory Data Analysis (EDA)
* Customer behavior analysis
* Data visualization using Python
* Business insight generation from data

---

# 🙋‍♂️ Author

## Akshay Besekar

* MBA in Business Analytics
* Aspiring Data Analyst
* Skilled in Python, SQL, Power BI, Excel, and Data Visualization



