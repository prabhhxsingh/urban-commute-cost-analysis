# 🚖 Public Transport vs Uber/Ola Price Comparison 🚇
by prabh

This data analysis project compares the **cost, travel time, wait time, and distance** between **public transport (e.g., metro, bus)** and **private cab services (Uber/Ola)**. It helps determine which mode is more efficient and economical for urban travel.
---
## 📁 Project Structure
 Public_Transport_vs_Uber_Analysis/
├── transportcost.csv # Dataset (manually created for real-world scenario)
├── analysis.ipynb # Python Notebook for EDA & visualization
├── dashboard.pbix # Power BI Dashboard file
├── assets/ # Folder for screenshots/exports
└── README.md # Project overview

## 📊 Tools Used
- **Python (Pandas, Matplotlib, Seaborn)**
- **Power BI** for interactive dashboard
- **Excel** to create and clean dataset

Python EDA
- Scatter Plot: **Cost vs Distance**
- Bar Charts: **Average Cost per Mode**, **Travel Time**
- Line Chart: **Total Cost Over Time**

### Power BI Dashboard
- 📅 Filter by date
- ☁️ Filter by weather
- 📊 Compare cost and travel time per mode
- 📈 View trends in cost over time

## 🧾 Sample Data Fields

| Date       | Mode   | From     | To       | Cost (₹) | Travel Time (min) | Wait Time (min) | Distance_km | Weather |
|------------|--------|----------|----------|----------|--------------------|------------------|-------------|---------|
| 2025-07-15 | Uber   | Lajpat   | CP       | 130      | 25                 | 5                | 7.5         | Cloudy  |
| 2025-07-15 | Metro  | Lajpat   | CP       | 40       | 28                 | 3                | 7.5         | Cloudy  |

## 📌 Key Findings

- Metro is **3x cheaper** on average than Uber for same routes.
- Uber can be faster at night, but costlier during peak hours.
- Weather doesn't drastically affect metro but increases Uber wait time.

Author
Prabhjot Singh

📧 [pprabhjot2805@gmail.com]

🔗 [www.linkedin.com/in/prabhjot-singh-3b4996317]