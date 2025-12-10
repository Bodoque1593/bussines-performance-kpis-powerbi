# Commercial Performance Dashboard – Real Estate Leasing KPIs 🏢📊

This repository contains a **Power BI dashboard** designed for monitoring the commercial performance of a real estate company.  
The report analyzes **leasing activity**, sales productivity of vendors, **sqm (m²) leased**, deal status, and goal tracking across different commercial segments and areas.

This is a real business case used internally to support strategic decision-making.

---

## 🎯 Business Problem

A real estate company needs to track **how effectively its commercial team is leasing spaces** across multiple business units.

Key questions include:

- How many **deals** has each vendor generated?
- Which deals were **successfully closed** vs. **lost**?
- How many **m²** (square meters) were leased per vendor, segment, or area?
- Are vendors reaching their **monthly or quarterly goals**?
- Which commercial segments (Premium, Medium, Standard) perform best?
- Which areas (Hotels, Logistic Parks, Shopping Malls, Offices) produce the highest volume of deals?
- What is the comparison between **expected targets vs. actual performance**?

This dashboard centralizes these KPIs to give management a clear and actionable view of commercial performance.

---

## 🗂️ Project Structure

```text
bussines-performance-kpis-powerbi/
│
├── report/
│   └── Aborigen-KPIs.pbix      # Main Power BI report (real estate leasing KPIs)
│
├── images/
│   ├── dashboard-overview.png  # Main KPI view
│   └── ventas-detalle.png      # Segments/areas detail
│
├── BI Comercializacion.Report/         # Original PBIP project files
├── BI Comercializacion.SemanticModel/  # Original semantic model
└── BI Comercializacion.pbip            # Original Power BI Project (editable structure)

🔍 Key KPIs & Business Metrics Included
🧑‍💼 Vendor Productivity

Total number of deals generated per vendor

Deals closed vs. not closed

Leasing performance by seller segment (Premium / Medium / Standard)

Vendor ranking by number of deals and m²

📐 Leasing Activity (m²)

Total m² leased vs. target

Average m² per transaction

m² contribution per commercial area:

Hotels

Logistic Parks

Shopping Centers

Office Spaces

🎯 Goal Tracking

% of goal achieved per vendor

Progress against monthly or quarterly targets

Expected vs. actual m² leased

Traffic-light indicators for performance

🏷️ Commercial Segmentation

Segmentation of deals by:

Premium segment

Medium segment

Standard segment

These segments represent categories of clients or property types, allowing deeper insight into where the company's commercial value is concentrated.

🏬 Commercial Areas

Performance breakdown for each area:

Hotels

Logistic Parks

Shopping Malls

Office buildings

This helps management understand which areas drive the most business and where to focus commercial effort.

🛠️ Tools & Techniques Used
Power BI Desktop

Data modelling with relationships between vendors, deals, and property areas

DAX measures for:

m² leased

Goal vs. achievement

Closed deals ratio

Segment and area scoring

Interactive slicers (segment, vendor, area, status)

Data Sources

Excel / CSV files exported from internal CRM

Vendor performance logs

Deal tracking database

Business Analysis Work

KPI definition with real stakeholders

Commercial segmentation (Premium / Medium / Standard)

Target-setting methodology

Performance reporting structure
