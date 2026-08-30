# 🇳🇿 NZ Telecom Support Ticket Analysis

## Overview
This project analyses 3,500 customer support tickets from a fictional 
NZ telecom provider to identify regional service quality patterns and 
customer satisfaction trends.

Drawing on my background in financial data analysis and compliance 
(ANZ Bank NZ, Hyundai Capital NZ), I applied statistical validation 
techniques — including KS statistics used in credit risk model 
validation — to assess whether customer satisfaction distributions 
differ significantly across regions.

## Business Questions
- Which regions generate the most support tickets?
- Do customer satisfaction (CSAT) scores differ significantly by region?
- What channels are customers using to raise issues?
- Which service plans have the highest complaint rates?

## Data
- Fictional NZ telecom support ticket dataset (2025)
- 3,500 records | 9 features
- Regions: Auckland, Wellington, Christchurch, and more

## Tools Used
- **Python** (pandas, matplotlib, scipy) — data analysis & statistics
- **SQLite** — data storage and SQL querying
- **Jupyter Notebook** — documented analysis workflow
- **KS Statistic** — distribution comparison across regions

## Key Findings
- Auckland generates the highest ticket volume, reflecting its 
  population dominance (~36% of NZ population)
- Auckland vs Wellington CSAT distributions show no statistically 
  significant difference (KS: 0.0287, p-value: 0.988)
- Average CSAT scores are consistently mid-range (3.4–3.5), 
  suggesting systemic service quality issues rather than 
  region-specific problems

## Skills Demonstrated
- SQL querying with SQLite
- Statistical analysis (KS test) applied to customer data
- Data visualisation with matplotlib
- Translating analytical findings into business insights
