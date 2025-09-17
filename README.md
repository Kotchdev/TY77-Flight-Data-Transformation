
## 📌 Project Overview
This project focuses on transforming a raw dataset into a structured model ready for analysis using Power BI.  
While many dashboards are built from clean data, real-world datasets are often messy. The goal of this project was to demonstrate how to use **Power Query** and **DAX** in Power BI to clean, model, and prepare data for reporting.  

---

## 🗂 Dataset
The dataset provided included inconsistencies such as:  
- Mixed data types (numbers stored as text, dates unformatted)  
- Missing/duplicate entries  
- Unstructured product/category information  

---

## 🔎 Transformation Process

### 1. Raw Dataset (Before)
![Raw Dataset Screenshot](./screenshots/s1.png)  
*Unstructured data with incorrect formats and duplicates.*

---

### 2. Transformation Steps
A few key transformations performed in **Power Query**:
- Converted Sales and Profit fields to **Currency** format  
- Split product details into **Category / Subcategory**  
- Cleaned missing values and removed duplicates  
- Standardized Date format  
- Created calculated columns and measures using **DAX**  

Example step:  
![Step Screenshot](./screenshots/s2.png)  
*Splitting Category into Category/Subcategory.*  

---

### 3. Cleaned Dataset (After)
![Cleaned Dataset Screenshot](./screenshots/s3.png)  
*Structured dataset ready for analysis and modeling.*  

---

## 📐 Data Model
![Data Model Screenshot](./screenshots/model.png)  
*Star schema built in Power BI, with fact and dimension tables connected.*  

---

## 📊 (Optional) Summary Dashboard
![Dashboard Screenshot](./screenshots/dashboard.png)  
*A simple validation dashboard showing record counts and summary sales figures after cleaning.*  

---

## 📊 Key Transformations & Insights
- **Merged tables** to combine travel location data with flight details, creating a single, enriched dataset.  
- **Grouped data by key columns** (e.g., flight month, airline, departure time, arrival time ) and aggregated metrics such as:  
  - Average duration of flights 
  - Average price across flights 
- Derived the time of day for flights from the flight hour
- The final dataset is structured, reliable, and ready for building dashboards or advanced analysis.  

---

## 🔑 Skills Demonstrated
- Data Cleaning & Transformation in Power BI (Power Query Editor)  
- Handling inconsistent data types, duplicates, and missing values  
- Merging multiple tables into a structured dataset  
- Grouping and aggregating columns (e.g., average duration, average price)  
- Building simple data models with relationships between tables  
- Creating calculated columns and basic DAX measures  
- Preparing datasets for future dashboarding and analysis  
- Clear documentation of the data preparation process

---

## 🚀 How to Use
- Download the `.pbix` file from this repo.
- Open it with **Power BI Desktop** (free from Microsoft).

---
