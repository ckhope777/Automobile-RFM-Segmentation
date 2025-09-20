![Python](https://img.shields.io/badge/Python-3.9-blue?logo=python)
![KNIME](https://img.shields.io/badge/KNIME-Analytics-yellow?logo=knime)
![Tableau](https://img.shields.io/badge/Tableau-Public-orange?logo=tableau)
![License](https://img.shields.io/badge/License-MIT-green)

# Automobile-RFM-Segmentation
Project applies RFM (Recency, Frequency, Monetary) analysis on three years of transaction data from an automobile parts manufacturer to uncover customer buying patterns. The results are used to build customer segments and recommend targeted marketing strategies.

## Methodology ##

1. **Data Preparation**
   - Imported and cleaned 3 years of transaction data.
   - Removed duplicates, standardized date/money formats.

2. **Feature Engineering**
   - **Recency** = Days since last purchase.
   - **Frequency** = Number of transactions.
   - **Monetary** = Total customer spend.

3. **RFM Scoring & Segmentation**
   - Scored customers on a **1–5 scale** for each metric.
   - Created combined **RFM scores (e.g., 555 = best, 111 = worst)**.
   - Grouped customers into segments (Champions, Loyal, At-Risk, Hibernating, Lost).

4. **Exploratory Data Analysis**
   - Python-based statistical summaries and plots.
   - HTML export for visual walkthrough.

5. **Visualization (Tableau)**
   - Dashboards to analyze segments by sales, recency, and frequency.
   - Dynamic filters for management decisions.

6. **Marketing Recommendations**
   - **Champions & Loyalists** → Exclusive offers, premium upselling.
   - **At-Risk & Hibernating** → Win-back campaigns, personalized discounts.
   - **Lost Customers** → Cost-effective outreach or deprioritization.

## Final Outcome ##
 - Identified **5+ customer segments** with distinct purchase behaviors.
 - Built **actionable marketing strategies** tailored to each group.
 - Delivered **interactive Tableau dashboards** for decision-makers.

## Tableau Dashboard ##
https://public.tableau.com/app/profile/chetan.khope/viz/MRA_17327060163640/OrdQuantityacrossCountries 

## Tech Stack ##
 - **KNIME Analytics Platform** → Data cleaning, preprocessing, and RFM scoring.
 - **Python (Jupyter Notebook)** → Exploratory analysis & validation.
 - **Tableau Public** → Interactive dashboards for customer segmentation insights.
