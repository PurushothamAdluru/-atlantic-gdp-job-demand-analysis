# Atlantic-GDP-Job-Demand-Analysis
A Power BI dashboard analyzing Atlantic Canada's GDP trends vs national job market demand using Statistics Canada datasets and Smart Narrative AI.


#  Case Study: Atlantic GDP & Job Demand Analysis with AI-Powered Power BI

###  Tools & Features Used

* **Power BI** for data modeling, interactive visuals, and dashboard storytelling
* **DAX (Data Analysis Expressions)** for custom calculated fields, KPIs, and dynamic insights
* **Smart Narrative (AI-powered)** to auto-generate contextual summaries based on user-selected filters, enabling real-time, human-readable insight delivery

---

##  Project Overview

This project analyzes how different industries contributed to **Atlantic Canada’s GDP growth between 2020 and 2024**, and whether that growth aligns with **national job vacancy trends**.

I built a **2-page interactive Power BI dashboard** featuring:

* A provincial GDP breakdown by industry
* National job demand visualized against regional output
* **AI Smart Narrative** for real-time, executive-friendly insights

---

##  Business Problem

**Objective:** Understand if Atlantic Canada’s top-performing industries are also those with the highest labor demand across Canada. This can help:

* Identify economic mismatches
* Guide provincial workforce planning
* Visualize job market dynamics by sector

---

##  Dataset Summary

**Sources:** [Statistics Canada](https://www.statcan.gc.ca)

1. **GDP by Industry & Province (Table 36-10-0402-01)**
   – Year: 2020 to 2024
   – Geography: Atlantic Provinces
   – Industry-level GDP in \$M

2. **Job Vacancies by Industry (Table 14-10-0372-01)**
   – Metrics: Job vacancy rate, number of vacancies, average wage
   – Geography: National
   – Year: 2020 to 2024

---

##  My Step-by-Step Approach

### **1. Data Cleaning & Modeling**

* Filtered for relevant provinces (NS, NB, PEI)
* Harmonized industry labels across both datasets
* Created DAX measures for:

  * GDP growth %
  * Total GDP
  * Vacancy rate trends

### **2. Design + AI Integration**

* **Custom color-coded legends** for visual clarity
* Structured all visuals to support filtering by **Industry**, **Province**, and **Year**
* Used **Smart Narrative AI** to auto-generate plain-language summaries:

  > “In 2024, the industry Finance and Insurance \[52] contributed \$25.37K, representing 21.07% of Atlantic GDP.”

 These AI narratives dynamically update with slicer changes — helping non-technical users make faster decisions.

---

##  Dashboard Highlights

**Provincial Breakdown: “How Industries Shaped Atlantic GDP Growth”**
![Screenshot 2025-06-03 192957](https://github.com/user-attachments/assets/0a671b4f-e874-4902-bc2c-b7386561e83d)

* Stacked column chart: GDP by Province & Industry
* Line chart: GDP trend by Year
* KPIs: Total GDP, Growth %

**GDP Comparison: “AI Narrative Insights: Job Vacancies & Demand”**
![Screenshot 2025-06-03 193111](https://github.com/user-attachments/assets/d6f92681-0b87-49a1-bd19-816c73eb0033)

* Vacancy rate trends (Canada-wide)
* Atlantic GDP vs Canada Job Demand (bar chart)
* Top in-demand industries (job count)
* AI-generated summary panel

---

##  Final Observations

| Insight               | Description                                                        |
| --------------------- | ------------------------------------------------------------------ |
| Finance & Insurance   | High GDP contributor in NS & NB, but mid-level national job demand |
| Arts & Entertainment  | Steady GDP growth, but lower demand nationally                     |
| Professional Services | Strong GDP presence + high national job vacancies                  |
| Smart Narrative AI    | Made insights accessible for non-technical users instantly         |

---

##  Final Thoughts

This project helped me merge **regional economics with national workforce analytics** using Power BI. More than visuals, the **AI integration elevated usability** — bringing clarity for both analysts and business users.

---

### What I’d Improve or Explore Next:

* Forecasting GDP with Power BI’s analytics pane
* Deeper provincial vs national wage comparison
* Role-level filtering (if available in future datasets)
