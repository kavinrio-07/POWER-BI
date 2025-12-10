# 📊 Healthcare Analytics Dashboard – Power BI Project  

An advanced and interactive "Healthcare Analytics Dashboard" built in "Power BI" to analyze hospital performance, state-wise healthcare distribution, total payments, and hospital type/category contributions across the United States.

This dashboard transforms raw healthcare data into meaningful insights for decision-making.

---

##  Project Overview  

The goal of this Power BI project is to provide a centralized analytical tool for:

- Understanding **hospital operations**  
- Tracking **total payments and dynamic measures**  
- Identifying **high-performing states and hospital types**  
- Comparing **hospital categories and service types**  
- Providing **location-based analysis** through maps  

The dashboard is organized into "three pages" — each offering a unique perspective on the dataset.

---

# Page 1 — Summary Overview

#  Visuals Included  
- Donut Chart → Dynamic Measure by Hospital Category  
- Bar Chart → Dynamic Measure by Hospital Type  
- Map Visualization → Provider State-level bubble map  

#  Insights  
- Specialty Centers and Geriatric Hospitals contribute the largest share of measured healthcare output.  
- Private Institutions dominate Dynamic Measure compared to Government, NHS, and Non-profit sectors.  
- Highest concentration of providers: California, Texas, Florida, New York.  
- Sparse provider activity in Alaska, North Dakota, Wyoming, and Montana.

---

# Page 2 — State & Hospital Type Analysis

# Visuals Included  
- Stacked Bar Chart → Dynamic Measure by Provider State and Hospital Type  
  - Hospital Types represented:
    - Government Funded  
    - National Health Service  
    - Non-Profit Organization  
    - Private Institution  

# Insights  
- "California, Texas, New York, and Florida" have the highest healthcare activity.  
- Private Institutions (purple) dominate in nearly every state.  
- NHS (blue) and Government-funded (light blue) show moderate contributions.  
- Many smaller states (VT, WY, ND, SD, DE) show very low healthcare activity.  
- This page helps identify:
  - Which states rely heavily on private healthcare
  - Which states have strong public/government healthcare presence
  - How hospital type distribution changes geographically

---

# Page 3 — Payment Summary & Dynamic Measure Details

# Visuals Included  
- KPI cards for each hospital type:
  - Government Funded
  - National Health Service 
  - Non-Profit Organization  
  - Private Institution  
- Values include:
  - Total Payments  
  - Dynamic Measure  

# Insights  
- Private Institutions have the highest total payments (₹82,31,66,274.19)
- NHS follows second with ₹33,69,46,690.40
- Government-funded and Non-profit hospitals show moderate totals.  
- The page serves as a financial summary dashboard showing:  
  - Payment totals by sector  
  - Contribution to Dynamic Measure  
  - Comparison of healthcare service funding  

---

# 📁 Files Included  

| File | Description |

| `Healthcare_Analytics.pbix` | Full Power BI dashboard |
| `data/` | Raw data files (CSV/Excel) used in the model |
| `images/` | Dashboard screenshots for GitHub preview |
| `README.md` | Project documentation |

---

# 🛠 Tools & Techniques Used  

# Power BI  
- Power Query (data cleaning & transformation)  
- Relationship modeling  
- DAX for calculated measures  
- Map visualizations  
- Drill-through filters  
- Dynamic slicers & interactive visuals  

# DAX Measures Used  
Examples:
- `Dynamic_Measure`
- `Total Payments`
- `Sum of Discharges`
- Category/Type Contributions (%)

---

# Future Enhancements  

- Add forecasting visuals for healthcare expenditure  
- Build a predictive model to estimate hospital demand  
- Integrate external data sources (U.S. Census, Medicare data)  
- Add State profile pages with drill-down features  
- Deploy the report using **Power BI Service** + Row-Level Security  

---

# 📫 Contact  
For any queries or collaboration opportunities, feel free to reach out or open an issue.

