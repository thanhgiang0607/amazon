# E-commerce Performance Insight Report
[![Python](https://img.shields.io/badge/Python-3.11-blue?style=flat-square&logo=python)]()
[![SQL](https://img.shields.io/badge/SQL-SQL-blue?style=flat-square&logo=sql)]()
[![Quarto](https://img.shields.io/badge/-Quarto-blue?style=flat-square&logo=quarto)]()
[![HTML](https://img.shields.io/badge/-HTML-orange?style=flat-square&logo=html)]()
[![Tableau](https://img.shields.io/badge/-Tableau-white?style=flat-square&logo=tableau)]()
## Overview
This project provides an enterprise-grade analysis of e-commerce sales performance and traffic acquisition efficiency for Q1 2026. The primary goal is to maximize **ROAS (Return on Ad Spend)** by identifying high-leverage opportunities for marketing optimization and ensuring the sustainability of "Anchor" product categories.

## 🚀 Live Report
[View the interactive report here](https://beautiful-puffpuff-4e95a0.netlify.app/)

## Core Analysis Goals
- **Revenue Dynamics**: Analyze total GMV vs. affiliate-driven GMV to assess platform dependency on external traffic.
- **Category Analysis**: Identify "Anchor" categories that provide business stability.
- **Channel Efficiency**: Map traffic volume against conversion rates (CVR) to identify "High-Value Drivers" vs. "Cost-Inefficient" channels.
- **Conversion Funnel**: Pinpoint friction points in the customer journey (the "Decision Gap").
- **Regional Performance**: Identify geographic hotspots for targeted regional marketing.
- **Customer Loyalty**: Assess the GMV contribution of New vs. Returning customers to identify retention gaps.

## Key Performance Indicators (KPIs)
- **Total GMV**: $38,906,883.00
- **ROAS**: Calculated based on affiliate GMV vs. commission costs.
- **Overall CVR**: 2.50%

## Tech Stack
- **Programming Languages**: Python, SQL
- **Data Analysis & Visualization**: Pandas, Plotly, NumPy
- **Reporting & Documentation**: Quarto, Bootstrap (for HTML styling)
- **BI Tools**: Tableau

## Project Structure
- `report.html`: The final rendered performance report.
- `report.qmd`: The Quarto source file containing the analysis logic, Python code, and narrative.
- `sql.ipynb`: SQL notebooks used for data extraction and preliminary processing.
- `data/`: Raw dataset containing sales, affiliate, behavior, and catalog data.
- `cleaned_data/`: Processed CSV files used for the final analysis.
- `dashboard.twbx`: Tableau workbook for high-level visualization.

## Strategic Recommendations
1. **Budget Rebalancing**: Shift 20% of budget from cost-inefficient channels to high-value drivers.
2. **CRO (Conversion Rate Optimization)**: Focus on the "Decision Gap" (Interest $
ightarrow$ Action) by introducing trust signals on product pages.
3. **Regional Focus**: Launch targeted campaigns in the top 3 performing states.
4. **LTV Maximization**: Implement a loyalty program to reduce reliance on expensive affiliate traffic.

## Recent Updates
- **Layout Fix**: Resolved a layout inconsistency in `report.html` where sections 5.3 and 6 were incorrectly sized. This was caused by premature closing tags in the HTML structure at the end of section 5.2.

## Getting Started
To regenerate the report:
1. Ensure all required data files are present in `data/` and `cleaned_data/`.
2. Use Quarto to render `report.qmd` to HTML.
