# edviron-revenue-analytics



EDVIRON Revenue & Settlement Analytics Dashboard

This project is a financial analytics case study built using Microsoft Excel (Power Query, Pivot Tables, VBA, and Dashboard Modeling).

The objective was to clean raw transaction data, normalize pricing structures (Flat vs Percentage), compute multi-layer revenue metrics, and build an interactive dashboard for business reporting.

🧠 Business Model Overview

Each transaction follows a 3-layer pricing structure:

Merchant Pricing – Pricing charged at school level

Partner Pricing – Pricing charged at ERP level

Edviron Buying – Cost incurred by Edviron

Revenue Calculations:

ERP Revenue = Merchant Pricing − Partner Pricing

Edviron Net Revenue = Partner Pricing − Edviron Buying

Edviron Gross Revenue = ERP Revenue + Edviron Net Revenue

⚙️ Key Features

✔ Raw data cleaning and normalization
✔ Flat vs Percentage pricing conversion to absolute INR
✔ Transaction-level revenue computation
✔ ERP payable and Edviron retained modeling
✔ Pending vs Settled exposure tracking
✔ Exception flagging (negative margins / pricing issues)
✔ Interactive dashboard with slicers
✔ VBA refresh automation

📈 Dashboard Highlights

Total Transactions

Gross Merchandise Value (GMV)

ERP Revenue

Edviron Net Revenue

Edviron Gross Revenue

Pending Exposure

Unique Users

Revenue split visualization

Gateway & Payment method analysis

Time-based trend analysis

All visuals dynamically update using slicers (Date, Partner, Gateway, Payment Method).

🛠 Tools Used

Microsoft Excel

Power Query

Pivot Tables & Pivot Charts

VBA (Macro automation)

🎯 Key Learnings

Multi-layer pricing modeling

Financial margin computation

Settlement and exposure analytics

Audit-friendly Excel structuring

Business-focused dashboard design

📂 Project Structure
Revenue_Analytics.xlsm
├── Raw_Data
├── Clean_Data
├── Calc_Model
├── Reports
├── Dashboard
└── Assumptions_Notes
📌 Author

Yeddula Ganesh Maruthi
Aspiring Data Analyst | AI/ML Engineer | Business Analytics Enthusiast

🔥 Extra Tip (To Make It Stronger)

Add:

3–4 dashboard screenshots

1 short demo video link

Clear folder structure

That makes your repo look professional and job-ready.
