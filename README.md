# Customer Behaviour Analytics

## Project Overview
Customer Behaviour Analytics is a data analysis project aimed at understanding customer purchasing patterns and shopping habits. The project analyzes customer transaction data to identify key trends, segment customers, and provide insights that can help businesses improve marketing strategies and enhance customer experience.

The analysis combines **SQL-based data exploration**, **Python-based analysis**, and **interactive dashboard visualization**.

---

## Tools & Technologies

![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-316192?style=for-the-badge&logo=postgresql&logoColor=white)
![pgAdmin](https://img.shields.io/badge/pgAdmin%204-336791?style=for-the-badge&logo=postgresql&logoColor=white)
![Power BI](https://img.shields.io/badge/Power%20BI-F2C811?style=for-the-badge&logo=powerbi&logoColor=black)

---

## Project Objectives

The main objectives of this project are:

- Analyze customer purchasing behavior
- Identify popular product categories
- Segment customers based on purchase history
- Understand the impact of discounts on purchasing behavior
- Visualize insights through an interactive dashboard

---

## Dataset Description

The dataset contains customer transaction and behavioral information including:

- Customer ID
- Age
- Gender
- Location
- Product Category
- Item Purchased
- Purchase Frequency
- Discount Applied
- Review Rating
- Previous Purchases
- Payment Method

This information helps in understanding customer buying patterns and preferences.

---

## Project Workflow

### 1. Data Loading
The dataset was loaded and explored to understand the structure, data types, and missing values.

### 2. Data Cleaning
Data preprocessing steps included:

- Handling missing values
- Checking data consistency
- Formatting columns for analysis

### 3. Data Analysis Using SQL
SQL queries were used to perform:

- Customer segmentation
- Category level analysis
- Discount usage analysis
- Top selling products analysis
- Customer purchase frequency analysis

Database operations were performed using **PostgreSQL and pgAdmin 4**.

---

### 4. Data Analysis Using Python

Python was used for exploratory data analysis including:

- Statistical summaries
- Distribution analysis
- Correlation analysis
- Data visualization

Libraries used:

- Pandas
- NumPy
- Matplotlib
- Seaborn

---

### 5. Data Visualization

An interactive **Power BI dashboard** was created to visualize insights such as:

- Customer distribution by category
- Top purchased products
- Discount usage trends
- Review ratings analysis
- Customer segmentation

---

## Key Insights

Some key insights derived from the analysis include:

- Identification of the most frequently purchased product categories
- Understanding how discounts influence customer purchases
- Insights into customer segments based on purchase history
- Analysis of product review ratings and customer satisfaction

These insights can help businesses improve marketing strategies and optimize sales performance.

---

## Project Structure

```
Customer_Behaviour_Analytics
│
├── data
│   └── customer_data.csv
│
├── sql_queries
│   └── customer_analysis.sql
│
├── notebooks
│   └── customer_analysis.ipynb
│
├── powerbi_dashboard
│   └── customer_dashboard.pbix
│
└── README.md
```

---

## How to Run the Project

### Clone the Repository
```
git clone https://github.com/Termu-101/Customer_Behaviour_Analytics.git
```

### Navigate to the Project Folder
```
cd Customer_Behaviour_Analytics
```

### Install Required Libraries
```
pip install pandas numpy matplotlib seaborn
```

### Run the Notebook
Open Jupyter Notebook and run the analysis notebook.

---

## Future Improvements

Potential future improvements for the project include:

- Building a **machine learning model for customer segmentation**
- Implementing a **recommendation system**
- Adding **predictive analytics for customer purchasing behavior**
- Creating a **real-time dashboard**

---

## Author

**Abhishek Khandge**

Master’s Student – Data Science  
University of Massachusetts Amherst
