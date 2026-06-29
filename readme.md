<a name="readme-top"></a>

<div align="center">
  <h1><b> MENA Digital Marketing Performance Analysis </b></h1>
</div>

<!-- PROJECT DESCRIPTION -->

#   📊 MENA Digital Marketing Performance Analysis <a name="about-project"></a>

## Overview 

This project presents an end-to-end exploratory data analysis (EDA) of digital marketing campaign performance across the **Middle East and North Africa (MENA)** region. Using Python, the project evaluates campaign effectiveness across multiple advertising platforms by analyzing marketing KPIs, customer engagement, conversion performance, and revenue generation.

The analysis transforms raw marketing data into actionable business insights that support data-driven decision-making for marketing teams and business stakeholders.

## 🎯 Project Objectives

The primary objectives of this project are to:

- Evaluate advertising performance across multiple marketing platforms.
- Measure campaign efficiency using key digital marketing KPIs.
- Analyze customer progression through the marketing funnel.
- Identify high-performing campaigns, creatives, and marketing themes.
- Assess the impact of seasonality and regional holidays on campaign performance.
- Provide actionable recommendations to improve marketing performance and optimize advertising spend.

---
## Data Sources 📊
- The dataset was provided in GitHub and was transformed to CSV format for transparency and reproductibility.


## Topical Questions and Hypotheses
#### Questions 🤔:

## ❓ Business Questions

This project addresses the following business questions:

1. Which advertising platforms deliver the highest Return on Ad Spend (ROAS)?
2. How effectively are customers progressing through the marketing funnel?
3. Which campaigns, creatives, and themes generate the strongest business results?
4. How do seasonality and regional holidays influence campaign performance across MENA markets?
5. Which countries and market tiers contribute the most revenue and conversions?

## 📂 Dataset

The project uses a **synthetic digital marketing performance dataset** designed for educational and portfolio purposes.

| Feature | Description |
|----------|-------------|
| **Region** | Middle East & North Africa (MENA) |
| **Period** | January 2023 – December 2025 |
| **Granularity** | Daily Campaign Performance |
| **Records** | 30,000+ |
| **Columns** | 35 |

The dataset simulates realistic advertising performance across multiple platforms, campaign objectives, and funnel stages using deterministic marketing relationships.

## 📊 Marketing KPIs

The analysis focuses on the following key performance indicators:

- 💰 Revenue
- 💵 Advertising Spend
- 📈 Return on Ad Spend (ROAS)
- 💲 Cost per Acquisition (CPA)
- 💳 Cost per Click (CPC)
- 📊 Click-Through Rate (CTR)
- 📉 Cost per 1,000 Impressions (CPM)
- 🎯 Conversion Rate
- 👀 Impressions
- 📢 Reach
- 🖱️ Clicks
- ✅ Conversions

---

## 🛠️ Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Jupyter Notebook
- Tableau (Dashboard Development)

---

## 🔍 Exploratory Data Analysis

The notebook covers:

- Data Inspection
- Data Cleaning
- Data Validation
- Descriptive Statistics
- Marketing KPI Analysis
- Platform Performance Analysis
- Funnel Analysis
- Campaign Performance Analysis
- Creative Performance Analysis
- Theme Performance Analysis
- Seasonality Analysis
- Geographic Performance Analysis
- Business Insights & Recommendations

### Data Dictionary
- customerID - Uniquely identify each customer
- gender - whether a customer is a Male or Female
- SeniorCitizen - whether customer is >60 years or not (Yes or No)
- Partner - Whether customer have a partner or not (Yes or No)
- Dependents - Whether customer have a dependents or not (Yes or No)
- tenure - How many months customer has been on the network
- PhoneService - Whether the customer is satisfied with the phone services
- MultipleLines - Whether the customer is satisfied with the multiple lines service
- InternetService - Whether the customer is satisfied with the internet service
- OnlineSecurity - whether the customer is satisfied with the online security service
- OnlineBackup - Whether the customer is satisfied with the onlince backup service
- DeviceProtection - Whether the customer is satisfied with the device protection service
- TechSupport - Whether the customer is satisfied with the tech support service
- StreamingTV - Whether the customer is satisfied with the streaming TV service
- StreamingMovies - Whether the customer is satisfied with the streaming Movies service
- Contract - Whether the customer opted for month-to-month, one-year and two-years contract with the Telco
- PaperlessBilling - Whether the customer is satisfied with the Paperless Billing service
- PaymentMethod - Whether the customer opted for electronic, mailed check, bank transfer and credit card payment methods
- MonthlyCharges - Monthly customer charges
- TotalCharges - Yearly customer charges
- Churn - Whether a customer will stop using the Telco's network or not (Yes and No)


The accompanying Tableau dashboard includes:

- 📌 Executive KPI Cards
- 📊 ROAS by Platform
- 🎯 Marketing Funnel Analysis
- 📈 Spend vs Revenue Scatter Plot
- 🏆 Top Campaign Performance
- 🎨 Top Creative Performance (Lollipop Chart)
- 🌳 Theme Performance (Treemap)
- 📅 Monthly Revenue Trend
- 🌍 Country Performance Map
- 🔥 Seasonality & Holiday Impact


<img width="1263" height="811" alt="Screenshot 2026-06-27 at 22 35 58" src="https://github.com/user-attachments/assets/c03d4a04-6149-4deb-a7f4-2188b48dbb9c" />
<img width="1264" height="818" alt="Screenshot 2026-06-27 at 22 35 38" src="https://github.com/user-attachments/assets/bd00717a-3615-4d1d-8737-5ddb7999a7f8" />
<img width="1260" height="815" alt="Screenshot 2026-06-27 at 22 36 25" src="https://github.com/user-attachments/assets/7c918f2c-94b6-4ff2-a657-205adf69bed5" />

---

## 💡 Key Insights

The analysis provides insights into:

- The most profitable advertising platforms.
- Campaigns delivering the highest revenue and conversions.
- Creative themes generating the strongest business impact.
- Customer progression through the marketing funnel.
- Seasonal trends affecting campaign performance.
- Revenue contribution across countries and market tiers.
- The relationship between advertising spend and generated revenue.


## 📁 Project Structure

```text
MENA-Digital-Marketing-Performance/
│
├── data/
│   └── digital_marketing_dataset_30k.csv
│
├── notebooks/
│   └── Mena.ipynb
│
├── dashboard/
│   └── Tableau Dashboard.twbx
│
├── images/
│
├── README.md
│
├── requirements.txt
│
└── LICENSE
```



## 🛠 Built With <a name="built-with"></a>

### Tech Stack <a name="tech-stack"></a>

<details>
<summary>Language</summary>
  <ul>
    <li><a href="https://www.python.org/">Python</a></li>
  </ul>
</details>


## Packages and Libraries 📚
#### Collection of significant Python Libraries:
- Pandas
- Numpy
- Seaborn
- Scipy
- Matplotlib

## 🚀 Installation

Clone the repository:

```bash
git clone https://github.com/yourusername/MENA-Digital-Marketing-Performance.git
```

Navigate to the project directory:

```bash
cd MENA-Digital-Marketing-Performance
```

Create a virtual environment:

```bash
python -m venv .venv
```

Activate the environment:

### Windows

```bash
.venv\Scripts\activate
```

### macOS/Linux

```bash
source .venv/bin/activate
```

Install the required packages:

```bash
pip install -r requirements.txt
```

Launch Jupyter Notebook:

```bash
jupyter notebook
```

Open:

```text
Mena.ipynb
```

## Cleaning the Data 🧹
#### We begin by thoroughly cleaning our data.
- Changing data types 
- Dealing with Nan values
- Replacing Values in categorical columns to be more consistent

## Visualizations 👀

- Line Chart 📈

<img width="1269" height="541" alt="Screenshot 2026-06-29 at 13 26 07" src="https://github.com/user-attachments/assets/d37d548a-2f42-4266-a8e6-ed31dbb9b595" />

- Bar chart 📊

<img width="1190" height="708" alt="Screenshot 2026-06-29 at 13 28 07" src="https://github.com/user-attachments/assets/88f72630-bd05-4723-96f7-e5b5fec10bc2" />

- lollipop Chart

<img width="1068" height="588" alt="Screenshot 2026-06-29 at 13 27 52" src="https://github.com/user-attachments/assets/91325286-51c4-46b4-b61f-46a80e96e84c" />


## Analysis 🔍
- Utilizing Python and data analysis libraries such as Pandas, Matplotlib, and Seaborn, we performed exploratory data analysis (EDA) to uncover trends and insights.



## ⚠️ Disclaimer

This project uses a **synthetic dataset** created solely for educational, analytical, and portfolio purposes. It does not contain real customer, campaign, or advertising data and should not be used for operational decision-making.

---

## 👨‍💻 Author

**Aminu Oluwarotimi Desmond**

**Data Analyst | Digital Marketing Data Analyst | Business Intelligence**

- GitHub: https://github.com/yourusername
- LinkedIn: https://linkedin.com/in/yourprofile

---

## ⭐ Support

If you found this project useful, please consider giving it a **⭐ Star** on GitHub. It helps others discover the project and supports my portfolio.

<p align="right">(<a href="#readme-top">back to top</a>)</p>

