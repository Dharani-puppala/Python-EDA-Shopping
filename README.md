# Exploratory Data Analysis (EDA) on Shopping Data 
Python(Jupyter Notebook)

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
  ![Image](https://github.com/user-attachments/assets/c8f5546d-4a4a-45e3-a6f7-4c0a6b20403a)
- **Step 2**: Generated a bar plot for Gender vs. Amount spent by grouping data and sorting it in descending order based on Amount values.
  ![Image](https://github.com/user-attachments/assets/2e2d41bb-df4d-446c-853a-2e02e2294c97)
- **Insight**: Most buyers are females, and their purchasing power is greater than males.

### **Plot 2: Age Group vs. Amount**
- **Step 1**: Created a count plot for Age Group using Seaborn, labeled values.
  ![Image](https://github.com/user-attachments/assets/49338c47-f246-4160-ad86-8992ac26f983)
- **Step 2**: Generated a bar plot for Age Group vs. Amount spent by grouping data and sorting it in descending order based on Amount values.
  ![Image](https://github.com/user-attachments/assets/57e2797a-37be-4a12-9718-256eee398fe6)
- **Insight**: Most buyers are women aged 26-35, while men aged 36-45 have the highest purchasing power.

### **Plot 3: Total Number of Orders from Top 10 States**
- **Step 1**: Created a bar plot for State vs. Number of Orders placed by grouping and sorting in descending order.
  ![Image](https://github.com/user-attachments/assets/8ef8c166-4659-4f40-b80b-c3cf8b41ec53)
- **Insight**: Most orders are placed from **Uttar Pradesh, Maharashtra, Karnataka**.

### **Plot 4: Total Amount/Sales from Top 10 States**
- **Step 1**: Created a bar plot for State vs. Total Sales.
- **Insight**: Highest sales are from **Uttar Pradesh, Maharashtra, Karnataka**.
  ![Image](https://github.com/user-attachments/assets/6761d041-2e18-4bf1-badb-ccccb714dc8c)
- **Observation**: Kerala is in the top 8 for order placements but not in top sales/profit generation.

### **Plot 5: Marital Status vs. Amount**
- **Step 1**: Created a count plot for Marital Status using Seaborn and labeled values.
  ![Image](https://github.com/user-attachments/assets/d7dc4936-c0bc-4f5d-a158-5b8214630a7c)
- **Step 2**: Generated a bar plot for Marital Status vs. Amount spent, applying `hue` for gender-based comparison.
  ![Image](https://github.com/user-attachments/assets/8fcc1716-a61e-4dab-820c-79a4ab5d715c)
- **Insight**: Married women have the highest purchasing power.

### **Plot 6: Occupation vs. Amount**
- **Step 1**: Created a count plot for Occupation using Seaborn and labeled values. 
![Image](https://github.com/user-attachments/assets/4f1ec9d6-f490-4338-bc42-9040ce277984)
- **Step 2**: Generated a bar plot for Occupation vs. Amount spent, sorting by descending Amount values.
  ![Image](https://github.com/user-attachments/assets/a68ff71e-19db-4ee8-931d-47a854908781)
- **Insight**: Most buyers work in **IT, Healthcare, and Aviation** sectors.

### **Plot 7: Product Category vs. Amount**
- **Step 1**: Created a count plot for Product Category using Seaborn and labeled values.
  ![Image](https://github.com/user-attachments/assets/2e472369-85a6-4db0-ada0-47a0c79c41a4)
- **Step 2**: Generated a bar plot for Product Category vs. Amount spent, sorting by descending Amount values.
  ![Image](https://github.com/user-attachments/assets/98f85cb8-22d7-4df5-b173-e633bb2ac41e)
- **Insight**: Most money is spent on **Clothing, Food, and Electronics**.

### **Plot 8: Product ID vs. Order (Top 10 Sold Products)**
- **Step 1**: Generated a bar plot for Product ID vs. Orders, sorting by descending Order values.
  ![Image](https://github.com/user-attachments/assets/028265a9-63db-44ed-a73f-c0177df96bf7)
- **Insight**: Most orders are placed for **P00265242, P00110942, P00237542**.

## **Key Insights**
- **Married women** aged **26-35** from **Uttar Pradesh, Maharashtra, and Karnataka** working in **IT, Aviation, and Healthcare** are the top buyers.
- Most purchases are made in **Clothing, Food, and Electronics** categories.

## **Technologies Used**

- **Python** (NumPy, Pandas, Matplotlib, Seaborn)
- **Data Visualization** (Seaborn, Matplotlib)
- **Excel**(CSV file)
- **Data Cleaning & Processing** (Pandas)


