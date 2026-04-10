# 🚲 NYC Citi Bike Data Analysis

## 📌 Project Overview
The goal of this project is to analyze user behavior, demographic trends, and trip patterns of NYC Citi Bike riders. By cleaning and visualizing the data, this project uncovers actionable business insights regarding who uses the service and when.

## 🛠️ Tools Used
* **Python:** Pandas for Data Cleaning & Aggregation
* **Data Visualization:** Matplotlib & Seaborn
* **Environment:** Google Colab / Jupyter Notebook
* **Spreadsheets:** Google Sheets (Pivot Tables & Initial Exploration)

## 🧹 Data Cleaning Process
Before analyzing the data, I used Python and Pandas to clean the raw dataset:
* Removed missing values (NaNs) and exact duplicate rows.
* Converted `Start Time` and `Stop Time` to official datetime objects.
* Stripped hidden white spaces from Station Names to ensure accurate grouping.
* Filtered out logical errors (e.g., trips where the Stop Time was before the Start Time, or Trip Duration was 0).

## 📊 Key Insights & Visualizations

### 1. User Demographics
The core user base is heavily skewed toward the **35-44 age bracket**, which accounts for the vast majority of total rentals. 
*(To add your image here in GitHub: just drag and drop your Column Chart image right into the editor window!)*

### 2. Weekday Commuters vs. Weekend Explorers
When breaking down rentals by day of the week and user type, a clear pattern emerges:
* **Subscribers** (annual members) dominate the weekdays, indicating they primarily use the bikes for daily commuting.
* **Customers** (one-time/short-term users) see a massive spike on Saturdays and Sundays.
*(Drag and drop your Grouped Bar Chart here)*

### 3. The 75+ Age Group Anomaly
While most age groups average similar trip durations, riders in the **75+ age bracket** have a massive spike, averaging trips of over 49 minutes. 
*(Drag and drop your Line Chart here)*

### 4. Top Pick-Up Locations
*(Drag and drop your Horizontal Bar Chart here showing the top 10 stations)*
