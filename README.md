# Microsoft Fabric Lakehouse Project

The main goal of this project was to create a Lakehouse architecture on Microsoft Fabric, applying modern data analytics steps such as data loading, SQL-based analysis, and Power BI visualizations. Additionally, the aim was to experience the power of combining Data Lake and Data Warehouse features, and explore how this architecture can be applied in real-world projects.

---

## Skills Gained

- Creating a workspace on Microsoft Fabric platform
- Understanding the Lakehouse architecture: Files vs Tables
- Loading a CSV file and using Delta Lake format for tables
- Querying data with SQL Analytics Endpoint
- Creating visual queries using Power Query
- Preparing reports and charts with Power BI
- Understanding the concept of Semantic Models (data models)
- Validating the end-to-end process

---

## Application Steps

### 1. Create Workspace
- Login to Microsoft Fabric portal
- Create a new workspace

### 2. Define Lakehouse
- Create a new Lakehouse structure using the "New Lakehouse" option
- Explore the Files and Tables sections

### 3. Load Data (CSV)
- Download the sales.csv file
- Upload it to the "data" folder within the Lakehouse

### 4. Convert Data to Table
- Create a "sales" table from the sales.csv file
- Explore the table structure using Delta Lake format

### 5. Query with SQL:
The purpose of the SQL query was to perform aggregate analysis and calculate the total revenue per product. This is a core part of data analysis, helping to determine how much revenue each product generates. The query works with parameters like "Item" (product) and "Quantity," and calculates the total revenue (Revenue) for each product. These kinds of analyses are crucial for understanding product performance and contributing to decision-making processes.

```sql
SELECT Item, SUM(Quantity * UnitPrice) AS Revenue
FROM sales
GROUP BY Item
ORDER BY Revenue DESC;
```

### 6. Create Visual Query
-	Group sales by the number of items and orders using Power Query

### 7. Reporting with Power BI
-	Create a table and a clustered bar chart using “Item” and “Quantity” data
-	Save the report as “Item Sales Report”


⸻

### Overall Evaluation

This project provided hands-on experience with modern data solutions offered by Microsoft Fabric. The use of both SQL-based and visual tools for analysis was demonstrated. The flexibility of Lakehouse architecture, along with powerful data management through Delta Lake and Power BI integration, was successfully applied. This experience lays a strong foundation for both the DP-700 exam and real-world data analytics projects.

⸻
### Screeshots

<img width="592" alt="1" src="https://github.com/user-attachments/assets/a656d503-e0df-4b3f-bb39-f8e676537fa4" />

<img width="1488" alt="2" src="https://github.com/user-attachments/assets/69f7d3f9-b2b2-4a1e-89a1-6b97df365e81" />

<img width="1461" alt="3" src="https://github.com/user-attachments/assets/a108d9ef-e264-4e86-82ad-28d1e644f902" />

<img width="1497" alt="4" src="https://github.com/user-attachments/assets/46211cfa-bd1d-426d-af39-b730cc8ccfa5" />

<img width="1450" alt="5" src="https://github.com/user-attachments/assets/9c3fde56-fc04-4a15-97a3-865489dfd0b4" />

<img width="1479" alt="6" src="https://github.com/user-attachments/assets/d75d933b-8fce-4345-a55f-8b6a033467d2" />

<img width="1238" alt="7" src="https://github.com/user-attachments/assets/af630337-d61a-4702-b51a-220a0ba74e58" />

<img width="1375" alt="8" src="https://github.com/user-attachments/assets/548f01eb-c064-4e67-8f00-7d337afe5da5" />










