# 🚖 Uber Rides Data Analysis

## 📌 Project Overview

This project explores **Uber ride trends in New York City** using time-series analysis, data visualization, and interactive dashboard creation.
The goal is to identify **peak hours**, **high-demand days**, and **top-performing dispatch bases**, delivering valuable insights for **operational efficiency** and **strategic planning**.

The analysis was conducted using **Python** for data preprocessing and **Power BI** for an intuitive and interactive dashboard.

---

## 📂 Dataset

* **Source:** [Kaggle - Uber Pickups in New York City](https://www.kaggle.com/datasets/fivethirtyeight/uber-pickups-in-new-york-city)
* **Records:** \~4.5 million Uber ride logs
* **Features:** Pickup date-time, location coordinates, and `dispatching_base_num`

---

## 🔍 Project Steps

### 1. **Data Preprocessing (Python)**

* Imported dataset and checked for missing values.
* Converted `Date/Time` to proper datetime format.
* Extracted **Hour**, **Day of Week**, and **Month** for trend analysis.
* Grouped and aggregated data for dashboard-ready insights.

### 2. **Exploratory Data Analysis (EDA)**

* Identified **peak pickup hours** and **busiest days**.
* Analyzed **monthly ride patterns**.
* Ranked **top 5 dispatch bases** by total rides.

### 3. **Power BI Dashboard Development**

* **KPIs:**
  * Total Rides
  * Average Rides per Day
  * Peak Hour

* **Visualizations:**
  * Time Trends (Line Chart: Date vs. Total Rides)
  * Rides by Hour of Day (Column Chart)
  * Weekday Patterns (Custom-sorted Bar Chart)
  * Dispatch Base Performance (Bar + Line combo chart for Top 5 bases)
* Clean, **landscape layout** for better presentation.

---

## 📊 Dashboard Preview

![Uber Rides Dashboard](https://github.com/AnuragKumar1712/Uber-Data-Analysis/blob/main/Dashboard%20(PowerBI)/Dashboard.png)

---

## 💻 How to Run Locally

### **Python Analysis**

1. Clone this repository:

   ```bash
   git clone https://github.com/AnuragKumar1712/Uber-Rides-Data-Analysis.git
   ```
2. Install dependencies:

   ```bash
   pip install pandas matplotlib seaborn
   ```
3. Run the Jupyter Notebook to generate insights:

   ```bash
   jupyter notebook
   ```

## 💡 Key Insights

* Peak demand observed during **evening rush hours (5–7 PM)**.
* Fridays and Saturdays consistently record **higher ride volumes**.
* Certain **dispatch bases handle a disproportionately high number of rides**, indicating operational concentration.

---

## 🛠 Tools & Technologies

* **Python:** Pandas, Matplotlib, Seaborn
* **Power BI:** For interactive dashboard creation
* **Jupyter Notebook**
* **Git & GitHub**

---

## ✍️ Author

**Anurag Kumar**
*Data Analyst & Full-Stack Developer*
🔗 [LinkedIn Profile](https://www.linkedin.com/in/anuragkumar1702/)

---
