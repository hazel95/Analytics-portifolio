# **Project Title**  
**Exploratory Analysis of Instacart Online Shopping**

---

## **Tools Used**  
**Power BI**, **DAX**, **Power Query**, **Excel**

---

## **Objective**  
To explore customer purchasing patterns, product popularity, and reorder behavior using the Online Instacart dataset.

---

## **Key Steps**

- **Data Preparation:** Imported and cleaned multiple CSV files (`orders`, `products`, `aisles`, `departments`).
- **Data Modeling:** Built relationships between tables and created calculated columns for analysis.

### **Exploratory Insights**
- Identified **most frequently reordered products** , **average time taken between reorders**
- Analyzed **average basket size per user**
- Ranked **departments by order volume**
- Explored **user engagement and product loyalty**

## **WHATS THE STORY BEHIND THE DATA & RECOMMENDATIONS**

- **Prioritize Restocking for High-Demand Categories**  
  Farm produce and dairy products show the highest reorder rates. These items should be restocked more frequently to meet consistent customer demand and reduce stockouts.

- **Optimize Delivery and Marketing Around Peak Times**  
  Most orders occur on **Mondays and Fridays**, especially between **10 AM and 6 PM**. Consider:  
  - **Scheduling more delivery slots** during these windows  
  - **Running promotions or reminders** during peak hours

- **Implement Smart Reorder Reminders**  
  Since the average reorder cycle is **10 days**, trigger personalized reorder notifications or
   discounts around **day 8–10** to encourage repeat purchases. 

- **Segment Customers by Reorder Behavior**  
  Identify loyal customers based on reorder frequency  using the table showing the top customers by total products ordered
   and target them with **tailored offers** or **subscription models** for essentials like dairy and produce.

- **Use Department-Level Insights for Inventory Planning**  
  Departments with lower reorder rates may need **seasonal promotions** or **bundling strategies** to boost engagement.
