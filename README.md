# 🏭 Manufacturing Performance & Operational Excellence Cockpit (Power BI)

An executive-level **Manufacturing & Shop-Floor Operations Dashboard** built in **Microsoft Power BI** to monitor Overall Equipment Effectiveness (OEE), production schedule attainment, on-time delivery (OTD), equipment downtime root causes, and scrap costs across manufacturing plants and work centers.

---

## 🖼️ Dashboard Preview

![Manufacturing Operation Excellence Cockpit Dashboard](./Manufacturing%20Operation%20Excellence%20Cockpit%20Dashboard.png)

---

## 🎯 Executive KPIs & Performance Summary

| KPI Metric | Current Value | Benchmark / Target | Variance / Status | Business Impact |
| :--- | :---: | :---: | :---: | :--- |
| **Avg OEE %** | **83.14%** | 85.0% (World-Class Goal) | `-1.9% vs Goal` | Tracks overall equipment availability, performance, and quality |
| **Schedule Attainment %** | **96.64%** | 0.18M / 0.19M Units | `+0.6% vs Plan` | Measures adherence to planned production volume |
| **On-Time Delivery (OTD %)** | **78.9%** | 90.0% (OTD Target) | `-11.1% vs Goal` | Highlights order fulfillment delays requiring plant-level action |
| **Total Downtime Hours** | **383.10 Hrs** | 0.88 Hrs / Order | `436 Total Orders` | Quantifies lost production capacity across shop-floor lines |
| **Scrap Cost (Cr)** | **₹1.51 Cr** | 1.9% Scrap Rate | `3,692 Scrapped Units` | Tracks material waste and quality-related financial loss |

---

## 📈 Visual Breakdown & Analytical Insights

1. **Multi-Dimensional Slicer Bar & Reset Control**
   * Filter metrics dynamically across **Company Code**, **Plant Name**, **Production Department**, and **Month Year**, complete with a one-click **Clear slicers** button.
2. **Planned vs. Actual Production Output (Combo Chart)**
   * Compares monthly **Good Output Qty** against **Planned Qty** (`GAMNG_Planned_Qty`) from April 2025 to March 2027 to track long-term production consistency.
3. **On-Time vs. Delayed Orders by Plant (Stacked Column Chart)**
   * Evaluates delivery performance across key facilities (*Bengaluru Main Plant, Hosur Precision Unit, Pune Stamping & Assembly, Chennai Electronics Hub, Hyderabad Aerospace Facility*).
4. **Downtime Hours by Root Cause (Horizontal Bar Chart)**
   * Identifies top operational bottlenecks—including *Power / Utility Failure*, *Unplanned Mechanical Breakdown*, *Material Shortage*, *Sensor / PLC Calibration*, *Quality Hold*, and *Tool Changeover*.
5. **Monthly OEE & Components Trend (Multi-Line Chart)**
   * Deconstructs **OEE %** into its three core pillars—**Availability %**, **Performance %**, and **Quality %**—to pinpoint whether efficiency dips stem from machine stops, slow cycles, or defects.
6. **Production Output & Scrap by Department (100% Stacked Bar Chart)**
   * Compares good output yield (`~97.7%–97.9%`) against scrap rates across *Machining, Assembly, Quality & Testing, Electronics, Logistics,* and *Fabrication*.
7. **Work Center Performance Table**
   * Provides granular shop-floor visibility into `Work_Center_Desc`, `Good Output Qty`, and scrap metrics across individual production lines (e.g., *5-Axis CNC Machining Line 1, Automated Assembly Line A, Robotic Welding Cell 1*).

---

## 🛠️ Technical Architecture & Skills Demonstrated

* **BI & Visualization:** Microsoft Power BI Desktop (Executive KPI cards with dynamic variance indicators, bookmark-driven *Clear Slicers* button, OEE component trend lines, 100% stacked yield bars)
* **Data Modeling & DAX:** OEE component aggregation (`Availability × Performance × Quality`), variance vs. plan/goal calculations, dynamic conditional formatting, and time-series trend analysis
* **Data Engineering & ETL:** Power Query data transformation, manufacturing order schema modeling, and plant/work-center hierarchy mapping

---

## 🔗 Project Links & How to Explore

* **GitHub Repository:** [View Full Project](https://github.com/gayathri2001kani-jpg/Manufacturing-Performance-Operational-Excellence-Cockpit)
* **How to Open:** Click on the `.pbix` file in the repository file list above, select **Download raw file**, and open it in **Microsoft Power BI Desktop**.
```[cite: 2, 4]

*(Note: Make sure the exact file `Manufacturing Operation Excellence Cockpit Dashboard.png` is uploaded to the main folder of this repository—and if you uploaded this Operations dashboard into a different repository URL than `Manufacturing-Performance-Operational-Excellence-Cockpit`, update the GitHub Repository link near the bottom before committing.)*
