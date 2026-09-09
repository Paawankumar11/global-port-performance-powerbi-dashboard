# 🌍 Global Port Performance & Trade Analytics Dashboard

## 📊 Project Overview

The **Global Port Performance & Trade Analytics Dashboard** is an interactive Power BI project designed to analyze global port activity, trade volume, imports, exports, and cargo performance.

The dashboard transforms large-scale port and trade data into interactive business insights using **Power BI, DAX, Power Query, data modeling, and data visualization**.

The project consists of two interactive dashboard pages: **Overview** and **Port Performance**, allowing users to explore port activity and trade performance across countries, ports, years, months, and cargo types.

---

## 🎯 Project Objectives

The main objectives of this project were to:

* Analyze global port activity and port-call volumes.
* Compare import and export activity.
* Identify the most active ports.
* Identify countries with the highest trade volumes.
* Analyze trade trends over time.
* Understand the distribution of different cargo types.
* Compare import and export volumes across cargo categories.
* Build interactive KPIs and filters for business-oriented analysis.
* Create a user-friendly dashboard for exploring port performance.

---

## 🛠️ Tools & Technologies

| Tool / Technology      | Purpose                                         |
| ---------------------- | ----------------------------------------------- |
| **Power BI**           | Dashboard development and visualization         |
| **DAX**                | Measures, KPIs, and calculated metrics          |
| **Power Query**        | Data cleaning and transformation                |
| **Data Modeling**      | Creating relationships and analytical structure |
| **Data Visualization** | Interactive charts, maps, KPIs, and slicers     |

---

# 📌 Dashboard Structure

## 1️⃣ Overview

The Overview page provides a high-level summary of global port activity and trade performance.

### Key Performance Indicators

The dashboard includes the following KPIs:

* **Total Port Calls**
* **Total Imports**
* **Total Exports**
* **Total Trade**
* **Active Ports**

### Interactive Filters

Users can dynamically filter the dashboard using:

* **Country**
* **Year**
* **Port Name**
* **Month**

### Visualizations

The Overview page includes:

* Total Port Calls by Port
* Total Port Calls by Country
* Top 10 Countries by Trade Volume
* Top 10 Ports by Port Calls
* Total Trade Trend Over Time
* KPI cards for major performance metrics

These visualizations allow users to quickly identify high-activity ports, major trading countries, and changes in trade activity over time.

---

## 2️⃣ Port Performance

The Port Performance page focuses on analyzing port activity across different cargo categories.

### Cargo Types Analyzed

The dashboard analyzes:

* **Container**
* **Dry Bulk**
* **General Cargo**
* **RoRo**
* **Tanker**
* **Cargo Total**

### Key Analysis

The page includes:

* Import distribution by cargo type
* Export distribution by cargo type
* Cargo-level performance comparison
* Interactive filtering by port, country, year, and month

This allows users to understand which cargo categories contribute most to overall port activity and how imports and exports differ across cargo types.

---

# 📐 DAX & Measures

Several DAX measures were created to support the dashboard's KPIs and analytical views.

### Example Measure

```DAX
Port Performance =
[Total Port Calls] +
DIVIDE([Total Trade], 1000000)
```

This measure combines port activity and normalized trade volume to create a comparative port-performance metric.

Other measures were developed for:

* Total Port Calls
* Total Imports
* Total Exports
* Total Trade
* Active Ports
* Cargo-level analysis
* Top-performing ports and countries

---

# 📷 Dashboard Preview

## Overview

![Overview Dashboard](Screenshots/overview.png)

## Port Performance

![Port Performance Dashboard](Screenshots/Port Performance.png)

---

# 🔍 Key Insights

The dashboard enables analysis of several important business questions, including:

### 🚢 Port Activity

Which ports have the highest number of port calls?

### 🌍 Country Performance

Which countries contribute the highest trade volumes?

### 📦 Cargo Analysis

Which cargo categories account for the largest share of imports and exports?

### 📈 Trade Trends

How does total trade change over time?

### 🔄 Import vs Export

How do import and export volumes differ across cargo categories and locations?

### 🏗️ Port Performance

Which ports demonstrate higher overall activity when considering both port calls and trade volume?

---

# 🧹 Data Preparation

The dataset required preparation before being used for dashboard development.

The data preparation process included:

* Data cleaning
* Handling missing and inconsistent values
* Data type corrections
* Date-related transformations
* Preparing fields for time-based analysis
* Structuring data for Power BI modeling
* Creating analytical measures using DAX

Power Query was used to prepare the data before building the final dashboard.

---

# 📊 Dashboard Features

### Interactive Slicers

Users can dynamically filter the dashboard by:

`Country → Year → Port → Month`

### KPI Cards

Quickly monitor:

`Port Calls → Imports → Exports → Trade → Active Ports`

### Geographic Analysis

A map-based visualization provides a geographical view of port activity across countries.

### Ranking Analysis

Top-performing ports and countries can be identified using ranking-based visualizations.

### Time-Series Analysis

Trade trends can be analyzed over time to identify changes in global port activity.

### Cargo Analysis

Import and export activity can be compared across major cargo categories.

---

# 💡 Business Questions Answered

This dashboard can help answer questions such as:

1. Which ports have the highest port-call activity?
2. Which countries have the highest trade volumes?
3. What is the overall import-to-export distribution?
4. Which cargo types contribute most to trade activity?
5. How does trade volume change over time?
6. Which ports are most active?
7. How does cargo composition differ between imports and exports?
8. How does port performance vary across countries and time periods?

---

# 🚀 Skills Demonstrated

This project demonstrates practical experience with:

* **Power BI**
* **DAX**
* **Power Query**
* **Data Cleaning**
* **Data Transformation**
* **Data Modeling**
* **KPI Development**
* **Interactive Dashboard Design**
* **Data Visualization**
* **Geospatial Analysis**
* **Time-Series Analysis**
* **Business Intelligence**
* **Data Analysis**

---

# 📁 Repository Structure

```text
port-performance-powerbi-dashboard/
│
├── 📁 PowerBI/
│   └── Global_Port_Performance_Dashboard.pbix
│
├── 📁 Screenshots/
│   ├── overview.png
│   └── Port Performance.png
│
├── 📁 Dataset/
│   └── dataset_info.txt
│
└── 📄 README.md
```

---

# 📚 Dataset

The project uses global port activity and trade-related data containing information about ports, countries, cargo categories, port calls, imports, exports, and trade activity.

The original dataset is not included in this repository if its size or licensing restrictions prevent redistribution.

Please refer to the dataset source and its original licensing terms before downloading or reusing the data.

---

# 🎓 Project Purpose

This project was developed as a **Data Analytics / Business Intelligence portfolio project** to demonstrate the ability to transform raw data into an interactive analytical dashboard.

The focus was not only on visualization but also on **data preparation, modeling, DAX calculations, KPI development, and extracting meaningful business insights from the data**.

---

## 👤 Author

**Paawan Tyagi**

Data Analytics | Power BI | SQL | Python

---

⭐ If you found this project useful, feel free to explore the repository and the dashboard.

