# 📊 SaaS Customer Churn Intelligence

## 📌 Project Overview

**SaaS Customer Churn Intelligence** is a data analysis project focused on exploring customer churn patterns in a Software-as-a-Service (SaaS) business. The project uses Python to clean, transform, analyze, and visualize customer data to identify patterns across industries, subscription plan tiers, payment statuses, countries, account managers, and customer activity dates.

The goal is to generate actionable insights that can help businesses understand customer churn and develop better customer retention strategies.

## 🎯 Project Objectives

- Analyze customer churn and identify churned customers.
- Explore churn patterns across different industries.
- Examine customer distribution by subscription plan tier.
- Investigate payment status categories.
- Compare customer counts across countries.
- Analyze churned customer distribution by account manager.
- Explore monthly and yearly patterns using customer last-active dates.
- Communicate findings through data visualizations.

## 🛠️ Tools and Technologies

- **Python** — Data analysis and manipulation.
- **Pandas** — Data cleaning, transformation, grouping, and aggregation.
- **Matplotlib** — Data visualization.
- **Seaborn** — Statistical graphics and categorical comparisons.
- **Jupyter Notebook** — Interactive analysis and documentation.

## 📂 Project Structure

```text
SaaS-Customer-Churn-Intelligence/
│
├── SAAS CHURN.ipynb
├── MP_Synthetics_50000_Rows.csv
└── README.md
```

*Note: The CSV file should be included in the project directory if you have permission to share the dataset.*

## 🔍 Project Workflow

1. **Data Loading:** Import the customer dataset using Pandas.
2. **Data Cleaning:** Standardize column names and inspect missing values, duplicate records, and data types.
3. **Data Transformation:** Convert date columns to datetime format and replace numeric churn labels with readable categories.
4. **Churn Identification:** Filter the dataset to focus on customers identified as churned.
5. **Exploratory Data Analysis:** Group customer records by industry, plan tier, payment status, country, account manager, and activity dates.
6. **Data Visualization:** Create bar charts and a line chart using Seaborn and Matplotlib.
7. **Insight Generation:** Summarize findings and identify areas for further investigation.

## 📈 Key Findings

### 1. Customer Churn by Industry

The notebook reports the following churned customer counts among the five leading industry categories:

| Industry | Churned Customers |
|---|---:|
| EdTech | 128 |
| DevTools | 121 |
| Logistics | 119 |
| MarTech | 113 |
| CyberSecurity | 112 |

EdTech recorded the highest count among these categories, making it a useful starting point for further customer retention investigation.

### 2. Payment Status Analysis

The notebook's written analysis reports the following payment status counts:

| Payment Status | Records | Percentage |
|---|---:|---:|
| Active | 513 | 56.0% |
| Failed | 294 | 32.1% |
| Pending | 109 | 11.9% |

The number of failed and pending payments suggests an opportunity to investigate billing issues and payment processing experiences.

### 3. Customer Distribution by Country

The notebook reports the following customer counts for selected countries:

| Country | Customers |
|---|---:|
| Singapore | 135 |
| USA | 126 |
| France | 125 |
| Germany | 115 |
| India | 112 |
| Canada | 109 |
| Australia | 99 |
| UK | 95 |

Singapore had the highest reported count, while the UK had the lowest among the listed countries. These figures represent counts, not market share or churn rates.

### 4. Additional Analysis

The notebook also explores:

- Customer distribution by plan tier.
- Customer counts by account manager.
- Yearly churned customer counts.
- Monthly churned customer patterns based on last-active dates.
- Feature adoption rate values among churned customers.

## 💡 Business Recommendations

- Investigate customer feedback, onboarding, and product engagement in industries with higher churn counts.
- Examine failed and pending payment records to identify potential billing or transaction issues.
- Review account manager workloads and customer support patterns.
- Monitor monthly and yearly churn trends to identify periods that may require additional retention efforts.
- Calculate churn rates for each industry and country using the total customer population in each segment.
- Investigate feature adoption and customer activity to identify possible retention opportunities.

## 🚀 How to Run the Project

### Prerequisites

Install Python and Jupyter Notebook, then install the required libraries:

```bash
pip install pandas matplotlib seaborn jupyter
```

### Steps

1. Clone or download this repository.
2. Place the CSV dataset in the project directory.
3. Open `SAAS CHURN.ipynb` in Jupyter Notebook.
4. Update the CSV file path in the notebook to match your local location.
5. Run the notebook cells in order to reproduce the analysis and visualizations.

**Important:** The original notebook uses a local Windows file path. Update the path before running the notebook on another computer.

## ⚠️ Limitations

- The analysis focuses primarily on customer counts rather than normalized churn rates.
- The findings describe observed patterns and do not establish the causes of churn.
- Payment status counts and other segment summaries should be verified against the relevant filtered dataset before drawing business conclusions.
- Further statistical analysis and customer-level investigation are needed to establish stronger conclusions.

## 👩‍💻 Author

**Osayi Chukwurimma Victoria**

- **Phone:** 08114569423
- **Email:** rimmavictoria82@gmail.com

## 🏁 Conclusion

This project demonstrates the use of Python for exploratory data analysis and visualization of SaaS customer churn. It highlights industry, payment status, geographical, and temporal patterns that can guide further investigation. The analysis provides a foundation for more advanced churn-rate calculations, customer segmentation, and predictive modeling.

---

*Prepared by Osayi Chukwurimma Victoria | SaaS Customer Churn Intelligence Project*
