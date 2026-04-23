# 🎆 Python Diwali Sales Analysis

## 📜 Project Overview
This project is a comprehensive **Exploratory Data Analysis (EDA)** of Diwali sales data using Python. The primary objective is to analyze customer purchasing behavior, discover demographic trends, and extract actionable business insights to help improve customer experience and optimize sales strategies.

## 🎯 Objective
- Perform data cleaning and preprocessing to ensure data quality.
- Conduct Exploratory Data Analysis (EDA) to understand purchasing patterns.
- Create visualizations to represent data distributions across various demographics.
- Formulate a data-driven conclusion to identify the core target audience.

## 📊 Dataset Description
- The dataset (`Diwali Sales Data.csv`) contains over **11,000 records** and **15 columns** detailing user transactions.
- Features include: `User_ID`, `Cust_name`, `Product_ID`, `Gender`, `Age Group`, `Age`, `Marital_Status`, `State`, `Zone`, `Occupation`, `Product_Category`, `Orders`, `Amount`.

## 🛠️ Tech Stack
- **Language:** Python
- **Libraries:** Pandas, NumPy, Matplotlib, Seaborn
- **Environment:** Jupyter Notebook

## 🧹 Methodology
1. **Data Cleaning:** 
   - Dropped empty/irrelevant columns (`Status`, `unnamed1`).
   - Handled missing values (dropped nulls in the `Amount` column).
   - Corrected data types for accurate mathematical operations.
2. **Exploratory Data Analysis (EDA):**
   - **Gender:** Analyzed the purchasing power and order counts between males and females.
   - **Age:** Evaluated which age brackets contributed the most to total sales.
   - **State:** Identified the top-performing states in terms of revenue and orders.
   - **Marital Status & Occupation:** Correlated spending habits with marital status and job sectors.
   - **Product Category:** Found the most popular product categories.

## � Key Findings & Insights
- **Gender:** Females have significantly higher purchasing power and order counts compared to males.
- **Age Group:** The **26-35 years** age group is the most active and spends the most.
- **Geography:** **Uttar Pradesh, Maharashtra, and Karnataka** are the top 3 states generating the highest revenue.
- **Occupation:** Buyers working in the **IT Sector, Healthcare, and Aviation** sectors are the top contributors to sales.
- **Product Categories:** **Food, Clothing & Apparel, and Electronics & Gadgets** are the most sold product categories.

## 🏆 Final Conclusion
> *Married women in the age group of 26-35 years from Uttar Pradesh, Maharashtra, and Karnataka, working in the IT, Healthcare, and Aviation sectors, are the most likely to buy products from the Food, Clothing, and Electronics categories.*

## � How to Run the Project
1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/Python_Diwali_Sales_Analysis.git
   ```
2. Navigate to the project directory:
   ```bash
   cd Python_Diwali_Sales_Analysis
   ```
3. Install the required dependencies:
   ```bash
   pip install pandas numpy matplotlib seaborn jupyter
   ```
4. Open the Jupyter Notebook:
   ```bash
   jupyter notebook Diwali_Sales_Analysis.ipynb
   ```

## 📺 References
- Based on the data analysis project tutorial: [Watch Video Here](https://www.youtube.com/watch?v=KgCgpCIOkIs)
