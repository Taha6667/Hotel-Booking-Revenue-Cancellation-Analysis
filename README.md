# 🏨 End-to-End Hotel Booking & Cancellation Analysis (Python & Power BI)

![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![Jupyter](https://img.shields.io/badge/Jupyter-F37626?style=for-the-badge&logo=jupyter&logoColor=white)
![Power BI](https://img.shields.io/badge/Power%20BI-F2C811?style=for-the-badge&logo=powerbi&logoColor=black)
![DAX](https://img.shields.io/badge/DAX-0078D4?style=for-the-badge&logo=microsoft&logoColor=white)

## 📌 Project Overview
A complete end-to-end data analytics project analyzing **115K+ hotel bookings** and **223K guests** across **City Hotels** and **Resort Hotels** (2014–2017). 

The workflow covers the entire data lifecycle: **Data Cleaning & Feature Engineering in Python**, **Exploratory Data Analysis (EDA)**, **Interactive BI Dashboarding in Power BI**, and **Executive PDF Reporting** to uncover revenue trends and mitigate the **36.05% cancellation rate**.

---

## 🖼️ Power BI Dashboard Preview

### Page 1: Executive Overview, Revenue & Seasonal Trends
![Overview & Revenue](Assets/page1_overview_revenue.png)

### Page 2: Customer Segmentation & Cancellation Drivers
![Cancellations & Segments](Assets/page2_cancellations_segments.png)

---

## 🎯 Key Performance Indicators (KPIs)
* **Total Bookings:** `115K`
* **Total Guests:** `223K`
* **Cancelled Reservations:** `42,647` (`36.05%` Cancellation Rate)
* **Repeated Guests:** `3,754`
* **Average Daily Rate (ADR):** `$97.11`

---

## 🛠️ Project Workflow & Repository Structure

### 1. Data Preparation & EDA (`Python_Scripts/`)
* **`Data Preparation.ipynb`**: Handled missing values, removed duplicates/outliers, corrected data types, and engineered new features (such as total stay nights and guest counts) to prepare a clean dataset (`hotel_booking.csv`).
* **`EDA_Hotel Booking Analysis.ipynb`**: Performed deep-dive statistical analysis and initial visualizations using Python (`Pandas`, `NumPy`, `Matplotlib`, `Seaborn`) to test hypotheses around seasonal pricing and booking cancellations.

### 2. Business Intelligence & Visualization (`Dashboard/`)
* Built a two-page interactive **Power BI** report (`Hotel Booking Analysis.pbix`) with custom **DAX Measures** and synchronized slicers (**Hotel Type**, **Year**, **Month**, **Reservation Status**).

### 3. Executive Documentation (`Reports/`)
* **`Hotel Booking Analysis.pdf`**: Detailed analytical report summarizing findings, statistical breakdowns, and strategic recommendations.
* **`Hotel Booking Dashboard.pdf`**: Static export of the interactive Power BI report for quick executive review.

---

## 💡 Key Analytical Insights & Recommendations
1. **Revenue & Seasonality:** **City Hotels** generate the majority of revenue, peaking in **2016** at **$12.1M** (vs. **$6.3M** for Resort Hotels). Both ADR and demand surge in **July–August** and drop sharply in **November–December**.
2. **Cancellation Drivers:** **Transient** customers booking with **No Deposit** account for the highest cancellations (`22,107`), while **Portugal (PRT)** leads all countries in cancelled reservations (`27K`). Implementing partial deposit policies during peak summer months is recommended to reduce revenue leakage.
3. **Customer Behavior:** **Online Travel Agencies (Online TA)** drive **46.64%** of bookings, **72.92%** of stays occur on **Weekdays**, **77.76%** prefer **Bed & Breakfast (BB)**, and **Room Type A** is the top choice (`85K` bookings).

---

## 👤 Author
**Taha Kamel**  
*Data Analyst | Microsoft Certified: Power BI Data Analyst Associate (PL-300)*  
[LinkedIn](https://www.linkedin.com/) | [GitHub](https://github.com/Taha6667)
