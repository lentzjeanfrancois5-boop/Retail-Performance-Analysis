# 📊 Retail Performance & Returns Analysis (YZG Consulting)

> **[Click Here to View the Interactive Dashboard on Tableau Public](https://public.tableau.com/your-link-here)** *(Note: Replace the link above with your actual Tableau Public URL)*

## 🏢 Business Overview
As a Data Analyst for YZG Consulting, I was tasked with analyzing retail order data to optimize scheduling and profitability. The client needed to understand which days of the week drive the most volume and where "profit leaks" (returns and unprofitable categories) are occurring.

---

## 🛠️ Technical Toolkit
* **Software:** Tableau Desktop
* **Advanced Features:** * **Dynamic Parameters:** Created a "Metric Switcher" using CASE statements to toggle between Sales, Profit, Orders, and Profit Margin.
    * **Container Layouts:** Used a rigid hierarchy of Horizontal and Vertical containers to maintain a pixel-perfect 1024x768 layout.
    * **Viz-in-Tooltip:** Integrated a weekday breakdown chart inside the map tooltips for geographic deep-dives.
    * **Action Filtering:** Implemented cross-sheet filtering to ensure a cohesive user experience.

---

## 📈 Forensic Insights Found
* **The Friday Volume Myth:** While Friday accounts for **17% of total orders**, it often carries a higher return rate for specific sub-categories compared to mid-week.
* **Continuous Deficit:** Identified **Tables** as a sub-category that remains unprofitable every single day of the week, suggesting a need for a shipping or pricing strategy audit.
* **Return Hotspots:** **California** was identified as the state with the highest return volume, specifically peaking on **Thursdays**.

---

## 📂 Project Structure
* `Tableau_Containers.twbx`: The packaged Tableau workbook containing the final dashboard and data extract.
* `Dashboard_Preview.png`: A high-resolution screenshot of the final UI.
* `README.md`: Documentation of the business case and technical methodology.

---

## 💡 How to Use
1. Use the **Metric Parameter** on the right to switch the entire dashboard between Sales, Profit, and Orders.
2. Filter by **Category** or **Return Status** to see how returns impact net profit.
3. Hover over any **State** on the map to see a pop-up chart of that specific state's weekly performance.
