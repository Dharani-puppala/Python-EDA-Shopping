# Exploratory Data Analysis (EDA) on Shopping Data 

## Project Overview
This project involves performing Exploratory Data Analysis (EDA) on shopping data using Python. The objective is to clean the data and generate visual insights to understand customer purchasing behavior.

## Steps Involved

### 1. Data Cleaning
1. **Import Libraries**: Imported necessary libraries including NumPy, Matplotlib, Seaborn, and Pandas.
2. **Import CSV File**: Loaded the dataset using `encoding='unicode_escape'` to handle encoding errors.
3. **Explore Dataset**:
   - Used `head()`, `shape`, `info()`, and `describe()` to analyze data properties.
4. **Handle Missing Data**:
   - Identified and dropped empty and null-valued columns.
5. **Adjust Data Types**:
   - Changed data types accordingly.
6. **Rename Columns**:
   - Standardized column names for clarity.

## 2. Exploratory Data Analysis

### **Plot 1: Gender vs. Amount**
- **Step 1**: Created a count plot for Gender using Seaborn, labeled values using `containers` and `bar_label`.
- **Step 2**: Generated a bar plot for Gender vs. Amount spent by grouping data and sorting it in descending order based on Amount values.
- **Insight**: Most buyers are females, and their purchasing power is greater than males.

### **Plot 2: Age Group vs. Amount**
- **Step 1**: Created a count plot for Age Group using Seaborn, labeled values.
- **Step 2**: Generated a bar plot for Age Group vs. Amount spent by grouping data and sorting it in descending order based on Amount values.
- **Insight**: Most buyers are women aged 26-35, while men aged 36-45 have the highest purchasing power.

### **Plot 3: Total Number of Orders from Top 10 States**
- **Step 1**: Created a bar plot for State vs. Number of Orders placed by grouping and sorting in descending order.
- **Insight**: Most orders are placed from **Uttar Pradesh, Maharashtra, Karnataka**.

### **Plot 4: Total Amount/Sales from Top 10 States**
- **Step 1**: Created a bar plot for State vs. Total Sales.
- **Insight**: Highest sales are from **Uttar Pradesh, Maharashtra, Karnataka**.
- **Observation**: Kerala is in the top 8 for order placements but not in top sales/profit generation.

### **Plot 5: Marital Status vs. Amount**
- **Step 1**: Created a count plot for Marital Status using Seaborn and labeled values.
- **Step 2**: Generated a bar plot for Marital Status vs. Amount spent, applying `hue` for gender-based comparison.
- **Insight**: Married women have the highest purchasing power.

### **Plot 6: Occupation vs. Amount**
- **Step 1**: Created a count plot for Occupation using Seaborn and labeled values.
- **Step 2**: Generated a bar plot for Occupation vs. Amount spent, sorting by descending Amount values.
- **Insight**: Most buyers work in **IT, Healthcare, and Aviation** sectors.

### **Plot 7: Product Category vs. Amount**
- **Step 1**: Created a count plot for Product Category using Seaborn and labeled values.
- **Step 2**: Generated a bar plot for Product Category vs. Amount spent, sorting by descending Amount values.
- **Insight**: Most money is spent on **Clothing, Food, and Electronics**.

### **Plot 8: Product ID vs. Order (Top 10 Sold Products)**
- **Step 1**: Created a count plot for Product ID using Seaborn and labeled values.
- **Step 2**: Generated a bar plot for Product ID vs. Orders, sorting by descending Order values.
- **Insight**: Most orders are placed for **P00265242, P00110942, P00237542**.

## **Key Insights**
- **Married women** aged **26-35** from **Uttar Pradesh, Maharashtra, and Karnataka** working in **IT, Aviation, and Healthcare** are the top buyers.
- Most purchases are made in **Clothing, Food, and Electronics** categories.

## **Technologies Used**

- **Python** (NumPy, Pandas, Matplotlib, Seaborn)
- **Data Visualization** (Seaborn, Matplotlib)
- **Excel**(CSV file)
- **Data Cleaning & Processing** (Pandas)


