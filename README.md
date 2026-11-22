# 🛍️ Customer Shopping Behaviour Analysis

## 📌 Overview

This project focuses on analyzing customer shopping behaviour to understand purchasing patterns, customer preferences, product performance, and sales trends.

The project uses Python (Pandas) for data loading, data cleaning, and Exploratory Data Analysis (EDA), PostgreSQL for SQL-based data analysis, and Power BI to build an interactive dashboard.

The main objective is to extract meaningful insights from customer shopping data and support data-driven business decisions.

## 📂 Dataset

The dataset contains customer shopping information, including:

- Customer ID
- Age and Gender
- Item Purchased
- Category
- Purchase Amount (USD)
- Location
- Season
- Review Rating
- Payment Method
- Subscription Status
- Previous Purchases
- Frequency of Purchases
- Shipping Type

## 🛠️ Tools & Technologies

- **Python:** Data analysis and processing
- **Pandas:** Data loading, cleaning, manipulation, and EDA
- **Jupyter Notebook:** Python development environment
- **PostgreSQL:** SQL queries and data analysis
- **pgAdmin:** Database management
- **Power BI:** Interactive dashboard and data visualization

## 🔄 Project Workflow

### 1. Data Loading (Python)
- Imported the dataset using Pandas.
- Explored the dataset structure.
- Checked column names, data types, and dimensions.

### 2. Exploratory Data Analysis (EDA)
- Analyzed customer purchasing patterns.
- Explored customer demographics.
- Identified trends in shopping behaviour.
- Examined different variables to understand customer preferences.

### 3. Data Cleaning
- Checked for missing values.
- Identified duplicate records.
- Corrected column names and data types.
- Prepared the dataset for further analysis.

### 4. SQL Analysis (PostgreSQL)
- Imported the cleaned dataset into PostgreSQL.
- Performed SQL-based analysis.
- Used filtering, grouping, and aggregate functions.
- Analyzed customer purchasing behaviour.
- Extracted meaningful business insights.

### 5. Power BI Dashboard
- Created an interactive Power BI dashboard.
- Designed KPI cards to track:
  - Number of Customers
  - Average Purchase Amount
  - Average Review Rating
- Created charts to analyze:
  - Revenue by Category
  - Sales by Category
  - Revenue by Age Group
  - Sales by Age Group
- Added interactive filters for Gender, Subscription Status, Category, and Shipping Type.

## 📊 Dashboard

The Power BI dashboard provides an overview of customer shopping behaviour through interactive visualizations and KPI cards.

**Key Dashboard Metrics:**

| KPI | Value |
|---|---:|
| Number of Customers | 3.9K |
| Average Purchase Amount | $59.76 |
| Average Review Rating | 3.75 |

The dashboard helps analyze customer preferences, category performance, age-group trends, and subscription behaviour.

## 📈 Results & Key Insights

The analysis helps understand:

- Customer purchasing preferences.
- Popular product categories.
- Revenue and sales patterns across categories.
- Shopping behaviour across different age groups.
- Customer subscription patterns.
- Payment and shipping preferences.

These insights can help businesses understand customer needs, improve marketing strategies, and make informed business decisions.

## 🚀 How to Run

### Prerequisites

Install the following tools:

- Python 3.x
- Jupyter Notebook
- PostgreSQL
- pgAdmin
- Power BI Desktop

### Steps

**1. Clone the repository**

```bash
git clone https://github.com/Yadav-navee/customer-shopping-behaviour-analysis.git
```

**2. Navigate to the project folder**

```bash
cd customer-shopping-behaviour-analysis
```

**3. Install Pandas**

```bash
pip install pandas
```

**4. Run Jupyter Notebook**

```bash
jupyter notebook
```

Open the Python notebook and execute the cells.

**5. Run SQL Queries**

- Open pgAdmin.
- Connect to your PostgreSQL database.
- Open and execute the SQL file available in the repository.

**6. Open Power BI Dashboard**

- Open the `.pbix` file using Power BI Desktop.
- Configure the data source if required.
- Explore the interactive dashboard.

## 📁 Project Structure

```text
customer-shopping-behaviour-analysis/
│
├── Dataset/
│   └── customer_shopping_behavior.csv
│
├── Python/
│   └── Customer_shopping_Behaviour_Analysis_Project.ipynb
│
├── SQL/
│   └── customer_behavior.sql
│
├── PowerBI/
│   └── customer_behavior_dashboard.pbix
│
└── README.md
```

## 👨‍💻 Author

**Naveen Yadav**

B.Tech Computer Science & Engineering

LinkedIn: [Naveen Yadav](https://www.linkedin.com/in/naveen-yadav-a56600303/)

---

⭐ If you find this project useful, feel free to explore the repository.
