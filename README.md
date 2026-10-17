# Hyundai Egypt | Executive Operations & Sales Dashboard

## Project Overview
An end-to-end Data Analytics and Business Intelligence solution modeled for **Hyundai Egypt**. This project simulates realistic automotive retail and after-sales maintenance operations (10,000 combined transactions) using **Python**, structured into a relational model via **Excel**, and visualized through an executive interactive **Power BI Dashboard**.

---

## Tech Stack & Workflow
1. **Python (Pandas, NumPy):**
   - Generated realistic synthetic data including vehicles, models, trims, regional branches, sales representatives, payment methods, and CSAT scores.
   - Applied vectorized logic for MSRP calculation, discounts, profit margins, and warranty vs. non-warranty maintenance costs.
2. **Excel & Data Modeling:**
   - Structured Star-Schema data model with Fact Tables (`Fact_Sales`, `Fact_Service_Maintenance`) and Dimension Tables (`Dim_Vehicles`, `Dim_Branches`, `Dim_Customers`, `Dim_Date`).
3. **Power BI Dashboard Design:**
   - Custom UX/UI utilizing the official Hyundai corporate color palette and anchor branding.
   - Interactive navigation buttons, drill-through capabilities, custom tooltips, and cross-filtering visuals.

---

## Key Business Performance Indicators (KPIs)
* **Revenue & Sales:** Total Sales Revenue, Gross Profit Margin %, Total Vehicles Sold.
* **After-Sales Operations:** Total Service Revenue & Customer Satisfaction Index (Avg CSAT).
* **Regional & Rep Breakdown:** Sales performance by governorate (Cairo, Alexandria, Dakahlia, Giza, Red Sea) and top sales representatives.
* **Payment Distribution:** Breakdown between Cash and Auto Finance / Installments.

---

## Project Structure
* `generate_data` – Python synthetic data generation script.
* `Hyundai_Egypt_BI_Dataset_10k.xlsx` – Multi-tab dataset containing 10,000 structured rows.
* `Hyundai.pbix` – Complete Power BI interactive dashboard file.
