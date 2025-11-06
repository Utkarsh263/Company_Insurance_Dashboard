# 📊 PRISM INSURANCE PVT. LTD. – Power BI Dashboard

## 🧩 Project Overview

This project showcases an interactive **Power BI dashboard** developed for **Prism Insurance Pvt. Ltd.**
The dashboard visualizes insurance claim data extracted from the company’s **SQL Server** database. It provides insights into policy performance, claim trends, premium distribution, and customer activity.

---

## 🏗️ Data Source and Preparation

### Data Extraction

* Data was sourced from the company’s SQL Server database using SQL queries.
* Tables used:

  * Customer
  * Policy
  * Claims
  * Payments

### Data Cleaning

Performed in Power BI Power Query:

* Removed null and duplicate records.
* Standardized column names and data formats.
* Validated relationships between policy, claim, and customer tables.
* Converted data types for numerical and date fields.

### Data Transformation

Derived new calculated columns to enhance analysis:

* **Age Group:** Classified customers into *Young Adult*, *Adult*, and *Elder* categories based on age.
* **Active/Inactive Policy:** Created a column based on policy end date or policy status.
* **Claim Status:** Grouped raw claim data into *Pending*, *Settled*, and *Rejected* for better visualization.

---

## 📈 Dashboard Features

### Key Metrics

* **Premium Amount:** 5.98M
* **Coverage Amount:** 600.55M
* **Claim Amount:** 16.91M

### Visuals and Insights

1. **Gender Distribution**
   Displays the number of male (5003) and female (5001) customers.

2. **Number of Claims by Claim Status**
   Bar chart showing claims categorized as *Rejected*, *Settled*, and *Pending*.

3. **Premium Amount by Policy Type**
   Visualizes premium contribution by policy types — Travel, Health, Auto, Life, and Home.

4. **Claim Amount by Age Group**
   Line and column chart showing total claim amount for each age group.

5. **Active vs Inactive Policies**
   Donut chart representing policy activity distribution — Active (67.76%) and Inactive (32.24%).

6. **Claims Summary Table**
   Matrix showing pending, rejected, and settled claim amounts by policy type.

### Interactivity

* **Slicers:** Added for Claim Number, Policy Number, and Customer ID to allow focused exploration.
* **Bookmarks:** Implemented for quick view switching (e.g., Column Chart vs. Remaining Balance Analysis).
* **Dark Theme:** Used for a modern and visually balanced design.

---

## 🧠 Insights & Key Takeaways

* Majority of the policies are **Active**, showing consistent engagement.
* **Travel policies** contribute the highest premium revenue.
* **Adult** customers have the highest claim amount share.
* **Rejected claims** are higher than **Pending**, suggesting strict claim evaluation.

---

## 💡 Tools & Technologies Used

* Power BI Desktop
* SQL Server
* Power Query Editor
* DAX (Data Analysis Expressions)
* Microsoft Excel (for interim validation)

---

## 🖼️ Dashboard Preview

![Dashboard Preview](./Screenshot%202025-11-06%20105206.png)

---

## 🚀 How to View the Dashboard

1. Open Power BI Desktop.
2. Load the `.pbix` file.
3. Connect to your SQL Server instance if required.
4. Press **F11** for Presentation Mode to view the dashboard full screen.

---

## 🧾 Author

**Utkarsh Kohli**

---

## 📜 License

This project is for educational and analytical purposes only.

