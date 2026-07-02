# 🏨 Data Cleaning & Reporting Automation Using Python & Power BI

## 📌 Project Overview

This project demonstrates an end-to-end **Data Cleaning & Reporting Automation** workflow using the **Hotel Booking Demand** dataset. The objective is to automate data preprocessing with Python and build an interactive reporting dashboard in Power BI.

The project focuses on improving data quality by handling missing values, removing duplicate records, standardizing data, creating new analytical features, and generating a clean dataset for business reporting.

---

## 🎯 Objectives

- Automate data cleaning using Python.
- Handle missing values and duplicate records.
- Standardize inconsistent data.
- Generate a clean dataset for analysis.
- Build an interactive Power BI dashboard.
- Improve reporting efficiency through automation.

---

## 🛠️ Tools & Technologies

- Python
- Pandas
- NumPy
- Matplotlib
- Jupyter Notebook
- Microsoft Excel
- Power BI

---

## 📂 Dataset

**Dataset Name:** Hotel Booking Demand

The dataset contains hotel booking information including:

- Hotel Type
- Booking Status
- Lead Time
- Arrival Date
- Customer Type
- Country
- Market Segment
- Distribution Channel
- Room Type
- Average Daily Rate (ADR)

---

## 📋 Project Workflow

```
Raw Dataset
      │
      ▼
Load Dataset (Python)
      │
      ▼
Data Inspection
      │
      ▼
Data Cleaning
 ├── Handle Missing Values
 ├── Remove Duplicate Records
 ├── Remove Unnecessary Columns
 ├── Convert Data Types
 └── Standardize Text Data
      │
      ▼
Feature Engineering
 ├── Total Guests
 ├── Total Nights
 ├── Total Revenue
 └── Booking Status
      │
      ▼
Export Clean Dataset
      │
      ▼
Power BI Dashboard
```

---

## 🧹 Data Cleaning Process

### Missing Values

Handled missing values in:

- `children`
- `country`
- `agent`

Removed the `company` column because it contained more than **94% missing values**.

---

### Duplicate Records

- Identified duplicate records.
- Removed **31,994** duplicate rows.

---

### Data Standardization

- Removed unnecessary spaces.
- Converted `reservation_status_date` to datetime format.
- Verified categorical values for consistency.

---

### Feature Engineering

Created the following new columns:

- `total_guests`
- `total_nights`
- `total_revenue`
- `booking_status`

These features enhance business reporting and dashboard analysis.

<img width="1918" height="1018" alt="image" src="https://github.com/user-attachments/assets/158aa691-9b2d-406b-8f14-39da0deb9560" />


---

## 📊 Power BI Dashboard

The cleaned dataset was imported into Power BI to create an interactive dashboard.
<img width="1135" height="637" alt="Screenshot 2026-07-03 020520" src="https://github.com/user-attachments/assets/df55a566-6357-4ba5-8299-6b98120b0d8f" />


### Dashboard Features

- 📌 Total Bookings
- 💰 Total Revenue
- 📈 Average ADR
- ❌ Cancellation Rate
- 📅 Monthly Booking Trend
- 🏨 Revenue by Hotel Type
- 🌍 Top Booking Countries
- 👥 Customer Type Distribution
- 📦 Market Segment Analysis
- 🛏️ Reserved Room Type Analysis
- 🎛️ Interactive Slicers

---

## 📁 Project Structure

```
Data-Cleaning-Reporting-Automation/
│
├── Dataset/
│   ├── hotel_bookings.csv
│   └── cleaned_hotel_bookings.csv
│
├── Notebook/
│   └── hotel_data_cleaning.ipynb
│
├── Reports/
│   └── Professional_Cleaning_Report.xlsx
│
├── PowerBI/
│   └── Hotel_Booking_Dashboard.pbix
│
├── Images/
│   └── dashboard.png
│
├── README.md
└── requirements.txt
```

---

## 📈 Key Results

- Cleaned the raw hotel booking dataset.
- Filled missing values.
- Removed duplicate records.
- Removed unnecessary columns.
- Standardized data types.
- Created additional analytical features.
- Exported a clean dataset for reporting.
- Built an interactive Power BI dashboard.

---

## 📚 Learning Outcomes

This project helped me gain practical experience in:

- Data Cleaning
- Data Preprocessing
- Python Automation
- Feature Engineering
- Business Intelligence
- Power BI Dashboard Development
- Data Reporting Automation

---

## 🚀 Future Enhancements

- Automated report generation
- SQL database integration
- Scheduled data refresh
- Cloud deployment
- Real-time Power BI dashboard

---

## 👨‍💻 Author

**Arun Kumar T**

If you found this project helpful, feel free to ⭐ star this repository.
