# Diwali Sales Data Analysis 🎉

## Objective  
The main goal of this project is to **improve customer experience by analyzing sales data** and **provide detailed insights to enhance customer satisfaction**.

---

## Table of Contents
- [Dataset Description](#dataset-description)
- [Project Workflow](#project-workflow)
- [Exploratory Data Analysis (EDA)](#exploratory-data-analysis-eda)
  - [Gender Distribution](#gender-distribution)
  - [Sales Based on Gender](#sales-based-on-gender)
  - [Age Group Analysis](#age-group-analysis)
  - [State-wise Sales and Orders](#state-wise-sales-and-orders)
  - [Marital Status Distribution](#marital-status-distribution)
  - [Occupation Insights](#occupation-insights)
  - [Product Category Insights](#product-category-insights)
  - [Top Customers Analysis](#top-customers-analysis)
- [Key Insights](#key-insights)
- [Technologies Used](#technologies-used)
- [Setup Instructions](#setup-instructions)

---

## Dataset Description

| Column Name       | Description                                      |
|-------------------|--------------------------------------------------|
| **User_ID**        | Unique identifier for the customer               |
| **Cust_name**      | Customer's name                                  |
| **Product_ID**     | Product identifier                               |
| **Gender**         | Gender of the customer (Male/Female)             |
| **Age Group**      | Age group of the customer                        |
| **Age**            | Actual age of the customer                       |
| **Marital_Status** | Whether the customer is married or not           |
| **State**          | State from which the customer belongs            |
| **Zone**           | Zone of the country                              |
| **Occupation**     | Customer's occupation                            |
| **Product_Category** | Category of the purchased product              |
| **Orders**         | Number of products ordered                       |
| **Amount**         | Total amount spent                               |

---

## Project Workflow

1. **Data Cleaning**: 
   - Removed duplicates and unnecessary columns (`Status`, `Unnamed`).
   - Handled missing values and formatted data types.

2. **Data Transformation**:
   - Gender and Marital Status columns reshaped for consistency.
   - Corrected column data types.

3. **EDA and Visualization**:
   - Visualized gender, age groups, marital status, state, and product categories.
   - Analyzed key spending patterns and customer behavior.

---

## Exploratory Data Analysis (EDA)

### Gender Distribution  
![Gender Distribution](path/to/gender_distribution.png)  
**Insight**: More female customers made purchases than males.

---

### Sales Based on Gender  
![Sales Based on Gender](path/to/sales_by_gender.png)  
**Insight**: Female customers contributed to a higher total sales amount than males.

---

### Age Group Analysis  
#### 1. Age Group by Gender  
![Age Group by Gender](path/to/age_group_by_gender.png)  
**Insight**: Age groups 26-35 and 36-45 show the highest spending patterns.

#### 2. Age Group by Amount  
![Age Group by Amount](path/to/age_group_by_amount.png)  
**Insight**: Age group 26-35 spent over ₹40 million, the highest among all groups.

---

### State-wise Sales and Orders  
#### 1. Amount Spent by Each State  
![State by Amount](path/to/state_by_amount.png)  
**Insight**: Uttar Pradesh recorded the highest spending at ₹19 million.

#### 2. Orders by State  
![Orders by State](path/to/orders_by_state.png)  
**Insight**: Uttar Pradesh leads with 4.8k orders, followed by Maharashtra and Karnataka.

---

### Marital Status Distribution  
![Marital Status](path/to/marital_status_distribution.png)  
**Insight**: Married individuals made more purchases than unmarried individuals.

---

### Occupation Insights  
![Occupation Distribution](path/to/occupation_distribution.png)  
**Insight**: Healthcare and IT professionals are the most frequent buyers, followed by the Aviation and Banking sectors.

---

### Product Category Insights  
#### 1. Product Category Count Plot  
![Product Category Count](path/to/product_category_count.png)  
**Insight**: Food and Clothing & Apparel have the highest counts, while categories like Furniture and Sports Products have fewer orders.

#### 2. Top 10 Product Categories by Amount  
![Top Product Categories](path/to/top_product_categories.png)  
**Insight**: Electronics, Clothing, and Food lead in total sales amount.

---

### Top Customers Analysis  
#### 1. Top 10 Customers by Amount  
![Top Customers by Amount](path/to/top_customers_by_amount.png)  
**Insight**: Vishakha is the top spender with ₹380k.

#### 2. Top 10 Customers by Orders  
![Top Customers by Orders](path/to/top_customers_by_orders.png)  
**Insight**: Customers like Aastha and Vishakha placed the most orders.

---

## Key Insights

1. **Age Group 26-35** spends the most.
2. **Uttar Pradesh, Maharashtra,** and **Karnataka** are the top-performing states.
3. **Clothing & Apparel** and **Food** dominate both in orders and revenue.
4. **Married customers** and those in **Healthcare & IT** fields are significant contributors.

---

## Technologies Used
- **Python**: Data Analysis (Pandas, NumPy)
- **Matplotlib & Seaborn**: Static visualizations
- **Plotly**: Interactive visualizations
- **Jupyter Notebook**: IDE for developing and running the code

---

## Setup Instructions
1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/diwali-sales-analysis.git
