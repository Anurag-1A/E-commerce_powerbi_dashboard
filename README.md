# E-Commerce Customer & Sales Dashboard (Power BI Project)

## Industry Context  
The global e-commerce industry has witnessed explosive growth over the past decade, driven by the convenience of online shopping, personalized marketing, and the rise of digital-first consumers. Understanding customer behavior, optimizing fulfillment processes, and leveraging data for personalized engagement have become critical success factors for online retailers.

## Project Objective  
Utilized **Power BI** to transform raw e-commerce data into meaningful business intelligence through:  
- Data cleaning and transformation  
- Data modeling and DAX  
- Building interactive, filterable dashboards  
The aim is to support **data-driven decisions** around **customer segmentation**, **geographical performance**, and **sales trends**, helping to refine customer engagement and sales strategies.

##  About the Dataset  
The dataset consists of two main tables:

**1. Customer Details**  
- CustomerID, Email, Country, Membership Type  
- SignUpDate, LastOrderDate, TotalSpent  
- Customer Communication Logs  

**2. Order Information**  
- OrderID, Customer Name, Product, Quantity  
- Unit Price, Order Date, Shipping Cost  

##  Data Preprocessing  
- **Missing UnitPrice values** were handled by imputing the **mean price**.  
- **Missing Product names** were filled using the **mode** (most frequent product).  
- Created calculated columns/measures like **Average Revenue Per Customer**, **Total Sales**, and **Monthly Trends** for better analytics.

## Actionable Insights  
1. **Seasonal Sales Spike:**  
   A sharp increase in sales is observed during **November to December**, suggesting **holiday and year-end seasonality**. Strategic promotions during this period can drive higher conversions.

2. **High-Spending Membership Segment:**  
   **VIP members** consistently contribute the highest revenue, followed by Premium and Standard members. Personalized loyalty benefits can help retain these valuable customers.

3. **Product-wise Cost Analysis:**  
   **Bikes** incur the **highest shipping cost**, followed by **Books** and **Laptops**.

4. **Product Performance Consistency:**  
   Across countries, **Shirts, Bikes, and Laptops** consistently show high order volumes, indicating strong and stable product categories that can be scaled.

5. **Sales Decline:**  
   Total order value has steadily declined from 2023 to 2025, with a drop of approximately 30%.This suggests a downward trend in revenue generation that may be tied to reduced order volumes, lower product pricing, or shifting customer demand.

---

## Dashboards

### Geographical Analysis Dashboard
![Geographical Analysis Dashboard](images/Geographical%20analysis%20dashboard.JPG)

### Sales & Order Trends Dashboard
![Sales and Order Trends Dashboard](images/Sales%20and%20Order%20Dashboard.JPG)

---

## Tools & Techniques Used  
- **Power BI**: Dashboarding, data modeling, DAX formulas  
- **Data Cleaning**: Missing value imputation (mean/mode), type conversion  
- **Interactive Filters**: Product, Country, Membership, Time Range  
- **Visualization Types**: Bar Charts, Time Series, Geo Maps, Cards  
