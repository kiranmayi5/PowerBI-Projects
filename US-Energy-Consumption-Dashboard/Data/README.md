# 📂 Data - US Energy Consumption

This folder contains the datasets used in the **US Energy Consumption Dashboard** project. The data has been organized into **raw** and **cleaned** versions to ensure transparency in the data processing pipeline.

---

## 📌 Dataset Overview
The datasets in this folder contain energy consumption data across the United States, segmented by state and energy source (Petroleum, Natural Gas, Coal, and Nuclear). The data was sourced from the [U.S. Energy Information Administration (EIA)](https://www.eia.gov).

---

## 📁 Files in this Folder

### 1️⃣ **Raw Data** (`Raw_Energy_Data.xlsx`)
- This file contains the **unprocessed** data directly imported from the data source.
- **Structure:**
  - Includes multiple years of data covering energy consumption patterns across various sources.
  - Data extracted without modifications for traceability.

### 2️⃣ **Cleaned Data** (`Clean_Energy_Data.xlsx`)
- This file contains the **processed and transformed** data used for dashboard development.
- **Cleaning Steps:**
  - **Data Formatting:** Converted numerical values, adjusted data types, and ensured accuracy.
  - **Energy Source Classification:** Ensured uniform categorization of energy sources.
- This cleaned dataset is used for building **visualizations and KPIs** in the Power BI dashboard.

---

## 📊 Data Processing Workflow

1️⃣ **Import Raw Data**  
2️⃣ **Clean & Transform using Power Query (Excel)**  
3️⃣ **Store as Clean Data**  
4️⃣ **Use in Power BI for Visualization & Analysis**  
