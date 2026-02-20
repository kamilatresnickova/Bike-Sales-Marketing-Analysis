# Bike-Sales-Marketing-Analysis

## Executive Summary

This project provides a comprehensive audit of a bike sales CRM campaign involving 5,000 leads. The analysis led to two critical findings:

**1. Ineffective Discount Strategy:** Increasing discounts up to 15% failed to drive any significant uplift in conversion rates but resulted in a $269,695 loss in potential profit.

**2. Data Integrity Issues:** The "flat" conversion trend identified across all segments suggests a potential tracking failure in the CRM system, leading to a formal Strategic Advisory for the data engineering team.

Through this project, I demonstrate proficiency in Power Query (data cleaning), Power Pivot & DAX (financial modeling), and Data Visualization (interactive dashboarding), while maintaining a critical mindset toward data quality.

## Dataset Overview & Preparation
**Original Data Source:** The core schema and initial records originated from this [Excel Tutorial dataset](https://github.com/AlexTheAnalyst/Excel-Tutorial/blob/b80a3c4f971a1608f2593ad8a585b53fbe74435e/Data%20Cleaning%20Excel%20Tutorial.xlsx).
**Dataset Expansion:** To simulate a large-scale CRM campaign, I utilized Gemini (Generative AI) to expand the original dataset to 5,000 unique leads, ensuring statistical significance for the analysis.
**Intentional Data "Dirtying":** For educational and auditing purposes, I utilized Gemini (Generative AI) to introduce "noise" and inconsistencies into the expanded dataset. This allowed me to demonstrate advanced Power Query cleaning techniques.

## Business Case
**1. Project Context:** The company executed a large-scale CRM campaign targeting 5,000 potential leads across three global regions (North America, Europe, Pacific). Regional managers were granted autonomy to apply various incentive levels (discounts ranging from 0% to 15%) to drive bike sales.
**2. Initial Objectives vs. Reality:** The original goal was to identify the "Sweet Spot" for discounts and segment customers by price sensitivity. However, during the exploratory data analysis (EDA) phase, the project shifted focus toward a critical profitability audit due to the discovery of highly unconventional data trends.
**3. Problem Statement - "The Discount Paradox":** The analysis revealed a significant strategic failure in the incentive program:
• Profit Erosion: High discounts (10–15%) were being applied without any measurable uplift in customer acquisition.
• Stagnant Conversion: The conversion rate remained "flat" across all discount tiers, suggesting that incentives were not driving the decision to purchase.
• Data Integrity Risks: The lack of correlation between price incentives and sales volume across all 5,000 leads raised a "Red Flag" regarding the reliability of the CRM tracking logic.
**4. Final Project Scope:** To address the findings, the project focused on the following key areas of data-driven auditing:
• Direct Margin Erosion Analysis: Calculated the exact financial impact of the discount strategy using Power Pivot and DAX. By creating a custom profit measure, the analysis proved that the 15% discount tier resulted in a $269,695 profit drop compared to the 0% tier, with no significant increase in customer acquisition.
• Regional Performance Tracking: Built an interactive system using Slicers to allow stakeholders to compare profitability across different territories (e.g., Australia vs. United Kingdom). This enables an immediate view of how regional managers' incentive decisions affected the bottom line.
• Data Reliability Evaluation: Instead of following a flawed dataset blindly, the project included a Data Quality Advisory. This serves as a strategic recommendation for the Data Engineering team to audit CRM tracking, as the observed "flat" conversion trends across 5,000 leads suggest potential technical inconsistencies.
**5. Key Deliverables:**
• Interactive Power BI/Excel Dashboard: A high-level view for stakeholders to monitor the inverse relationship between discounts and profit.
• Segment Neutrality Report: Evidence showing that demographics (children, commute distance, etc.) did not react to price changes as expected in a typical market.
• Technical Audit Recommendation: A formal advisory for the Data Engineering team to investigate potential "Flatline" data capturing errors in the CRM.

<img width="1032" height="501" alt="Snímek obrazovky 2026-02-20 v 20 33 15" src="https://github.com/user-attachments/assets/562f005b-58ea-423e-9bf6-1a574134f76e" />

## Technical Stack & Skills Demonstrated
This project serves as a showcase of my ability to handle complex data workflows and derive actionable business intelligence.

**Data Engineering & Cleaning (Power Query)**
• Source Integration: Connected and transformed raw data from disparate sources, including simulated large-scale datasets.
• Data Sanitization: Handled missing values, corrected inconsistent regional naming conventions, and standardized currency formats to ensure a "Single Source of Truth."
• Data Expansion: Leveraged Generative AI (Gemini) to create a statistically significant testing environment of 5,000 records.

**Data Modeling (Power Pivot)**
• Relational Schema: Designed a 1:N (one-to-many) star schema, connecting Dimension tables (Territory, Product, Customer) to Fact tables (Sales).
• Advanced Analytics (DAX): Developed custom measures using DAX formulas (e.g., IF, SUM, arithmetic operators) to calculate unit-level profit and conversion rates.

**Business Intelligence & Visualization**
• Interactive Dashboarding: Created a professional-grade UI on a custom background, featuring Combo Charts for trend comparison.
• Dynamic Filtering: Implemented Slicers (Country) to allow stakeholders to perform real-time drill-downs into regional performance.
• Data Storytelling: Translated complex technical findings into a concise "Executive Summary" and an "Advisory Box" to guide management decisions.











