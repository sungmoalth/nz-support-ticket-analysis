# 🇳🇿 NZ Telecom Support Ticket Analysis

## Overview
This project analyses 3,500 customer support tickets from a fictional 
NZ telecom provider to identify regional service quality patterns and 
customer satisfaction trends.

Drawing on my background in financial data analysis and compliance 
(ANZ Bank NZ, Hyundai Capital NZ), I applied statistical validation 
techniques — including KS statistics and AUROC used in credit risk 
model validation — to assess customer satisfaction patterns across 
regions.

## Business Questions
- Which regions generate the most support tickets?
- Do customer satisfaction (CSAT) scores differ significantly by region?
- Can we predict customer dissatisfaction using region, channel, and plan?
- What factors most influence CSAT outcomes?

## Data
- Fictional NZ telecom support ticket dataset (2025)
- 2,633 records with valid CSAT scores | 9 features
- Regions: Auckland, Wellington, Christchurch, and more

## Tools Used
- **Python** (pandas, matplotlib, scipy, scikit-learn)
- **SQLite** — data storage and SQL querying
- **Jupyter Notebook** — documented analysis workflow
- **Random Forest Classifier** — CSAT prediction model
- **KS Statistic** — distribution comparison across regions
- **AUROC** — model performance validation

## Key Findings
- Auckland generates the highest ticket volume, reflecting its 
  population dominance (~36% of NZ population)
- Auckland vs Wellington CSAT distributions show no statistically 
  significant difference (KS: 0.0287, p-value: 0.988)
- Random Forest model achieved AUROC of 0.52, suggesting that 
  region, channel, and plan alone are insufficient predictors of 
  CSAT — indicating systemic service quality issues rather than 
  location or plan-specific problems
- Region is the most influential feature (importance: ~0.40), 
  followed by Plan (~0.35) and Channel (~0.20)

## Skills Demonstrated
- SQL querying with SQLite
- Statistical analysis (KS test) applied to customer data
- Machine learning (Random Forest) with AUROC validation
- Feature importance analysis
- Translating low model performance into meaningful business insights
