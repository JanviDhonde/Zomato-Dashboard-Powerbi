# Zomato-Dashboard-Powerbi
mmm
# Zomato Analytics Dashboard in Power BI

## 📊 Project Overview
This Power BI dashboard offers detailed insights into Zomato’s operations across cities, focusing on:  
- **Order quantity and sales trends**  
- **Customer behavior**: Gained and lost customers  
- **Restaurant performance**: Ratings and active users  
- **City-level analysis**: Sales distribution and customer activity  

---

## Datasets Used
The following datasets were used in this project:

1. **Food**  
   - `f_id`, `item`, `veg_or_non_veg`

2. **Menu**  
   - `menu_id`, `r_id`, `f_id`, `cuisine`, `price`

3. **Orders**  
   - `order_date`, `sales_qty`, `sales_amount`, `currency`, `user_id`, `r_id`

4. **Order Type**  
   - `Order_Id`, `Type`

5. **Restaurant**  
   - `id`, `name`, `country`, `city`, `rating`, `rating_count`, `cuisine`, `link`, `address`

6. **Users**  
   - `user_id`, `name`, `age`, `gender`, `marital_status`, `occupation`

---

## Key Measures  
The following measures were created to drive insights in the dashboard:

- **ActiveUsers**  
- **CurrentYear**  
- **CurrentYrSale**  
- **Dynamic_Title**  
- **GainCustomers**  
- **LostCustomers**  
- **Order_count**  
- **PreviousYear**  
- **PreviousYrSale**  
- **Rating_Count**  
- **Sales**  
- **Subheading**  
- **Top_N_Sales**  
- **UserCount**

---

## Data Transformation in Power Query  
Data transformations were performed to clean and prepare the data before visualization. These included:  
- Merging datasets for comprehensive insights.  
- Creating calculated columns for better categorization.  
- Filtering irrelevant data to enhance performance.

---

## 📈 Dashboard Overview  
The dashboard contains the following visual pages:  

### **1. Overview Page**  
- Displays total quantity, sales, ratings, and order count.  
- Breakdown of food items by category: Veg, Non-Veg, and Other.  
- Visualizes top-performing cities by sales and a trendline of yearly sales growth.

### **2. User Performance Page**  
- Overview of total users, active users, and orders placed.  
- Insights into gained and lost customers with gender distribution.  
- User distribution by age group.

### **3. City Analysis Page**  
- Detailed city-wise analysis of sales, orders, gained and lost customers.  
- Comparison of cities based on ratings and active users.
