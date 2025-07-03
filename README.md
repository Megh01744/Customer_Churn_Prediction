# Customer_Churn_Prediction

 Telco Customer Churn Analysis (Python Project)

This project analyzes customer churn behavior in a telecom company using Python. The goal is to uncover insights into what drives customer attrition using exploratory data analysis — **no machine learning models were used**.

---

##  Dataset

- **Source**: [Telco Customer Churn - IBM Sample Data](https://www.kaggle.com/datasets/blastchar/telco-customer-churn)
- **File**: `WA_Fn-UseC_-Telco-Customer-Churn.csv`

---

## Tools Used

- Python
- Pandas, NumPy
- Seaborn, Matplotlib
- Jupyter Notebook

---

## Data Preprocessing

- Removed customer ID column
- Handled missing values in `TotalCharges`
- Converted `TotalCharges` to numeric
- Encoded categorical columns using `factorize()`

---

## Exploratory Data Analysis (EDA)

- **Churn Distribution** bar plot
- **Correlation Heatmap** to examine relationships between features
- **Tenure Segmentation**: Created a `TenureGroup` column
- **Service Usage Impact**: Explored churn based on services like `TechSupport`, `StreamingTV`, `OnlineSecurity`

---

## Business Insights (No ML)

- Customers with higher monthly charges tend to churn more
- Lack of tech support is linked to higher churn
- New customers (tenure < 1 year) are more likely to leave
- Month-to-month contract holders show the highest churn rate

---

## Project Highlights

- Built with clean, readable code in Jupyter Notebook
- EDA-focused, business-oriented analysis
- Includes actionable recommendations based on data

---

## Files Included

- `telco_churn_analysis(2).ipynb` – Jupyter Notebook with full code
- `README.md` – This file
  

---

## Contact

For questions or suggestions, feel free to connect via LinkedIn or GitHub!
https://www.linkedin.com/in/meghna-dey-a5906a305?lipi=urn%3Ali%3Apage%3Ad_flagship3_profile_view_base_contact_details%3BFuubh9VsQxaCAlCIJ8D4xQ%3D%3D
