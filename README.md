# Adidas Sales Performance Dashboard - USA

## 📘 Project Overview
This Excel project involves creating a dynamic and comprehensive sales performance dashboard for Adidas USA (2020 - 2021). By utilizing advanced data cleaning, pivot tables, and interactive visualization techniques, the project transforms raw sales records into actionable business insights. The final product is a user-friendly, interactive dashboard that allows stakeholders to explore sales distribution across different states, channels, retailers, and product types.

<img width="1846" height="686" alt="Screenshot 2026-06-21 225929" src="https://github.com/user-attachments/assets/3606e3c1-7d79-49ff-a0fa-95f9741a2d9e" />


## 📊 Data Set
* **Dataset Description:** The project utilizes the Adidas US Sales dataset, containing transactional data regarding sales methods, product categories, regional placements, and financial metrics (Revenue, Units Sold, and Profit margins).
* **Source Files:** Raw data processed directly within the workbook.

## ⚙️ Key Steps in the Project
* **Data Cleaning & Preparation:** Identified and handled missing values, corrected data types, and standardized categorical parameters to ensure data integrity.
* **Working Sheet Isolation:** Segregated raw transactional logs from working calculation sheets to preserve data history while executing complex metrics.
* **Pivot Table Architecture:** Structured highly efficient underlying Pivot Tables to segment revenue, profit, and volume aggregates across multiple business dimensions.
* **Interactive Controls & Navigation Integration:** Configured cross-filtering slicers (Retailer, Product, Years, Region) alongside a custom VBA-powered toolbar featuring an instant **"Reset View"** mechanism and a **"Full Screen Mode"** toggle for an immersive, presentation-ready dashboard view.
* **Dashboard Design & Customization:** Assembled clean visual layouts by customizing chart titles, labels, corporate-aligned color palettes, and hiding gridlines to ensure a modern web-app feel.

## 🧩 Dashboard Components
* **Total Sales by Sales Method:** A breakdown donut chart illustrating revenue splits between In-Store, Online, and Outlet channels.
* **Monthly Sales and Profit Trend:** A dual-line chart mapping operational trends over time to identify seasonal peaks.
* **Units Sold per Product Category:** Horizontal volume charts evaluating performance rankings among footwear and apparel categories.
* **Region-Wise Total Sales:** Multi-tiered bar representations capturing regional performance segments by channel.
* **Geographical and Retailer Breakdowns:** Detailed cluster bar graphs breaking down metrics across individual states (e.g., California, New York, Texas) and core distributors (Amazon, Foot Locker, Kohl's, Sports Direct, Walmart, West Gear).

## 🛠️ Tools & Tech Used
* **Microsoft Excel:** 
  * **Data Cleansing:** Used Power Query / Data Tools to remove duplicates, handle blank fields, and standardize data formats.
  * **Analytical Engine:** Built complex Pivot Tables to aggregate large-scale sales, profit, and volume metrics across various dimensions.
  * **Data Visualization:** Designed custom dynamic charts (Donut, Line, and Horizontal Bar charts) formatted cleanly to match a professional UI theme.
* **VBA / Macro Automation:** 
  * Written custom VBA scripts to automate operational dashboard controls.
  * Configured a global state-reset macro to instantly clear all active slicer filters.
  * Programmed a screen-state toggle macro to hide the Excel ribbon/gridlines for an immersive, application-like experience.

## 🚀 Instructions for Use
1. Clone or download this GitHub repository to your local machine.
2. Open the `.xlsm` file (ensure you enable Macros when prompted to allow the custom button functionality to work).
3. Interact with the multi-select Slicers on the right panel to filter specific market segments.
4. **Dashboard Toolbar Controls (Top Right):**
   * Click the **Reset Icon (🔁)** to instantly clear all active filters at once.
   * Click the **Monitor/Screen Icon (🖥️)** to toggle the full-screen view, hiding the Excel ribbon and gridlines for a clean dashboard application experience.
