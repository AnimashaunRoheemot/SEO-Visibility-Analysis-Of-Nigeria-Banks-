#  SEO Visibility Analysis of Nigerian Banks

## Table of Contents
1. [Overview](#overview)  
2. [Business Objective](#business-objective)  
3. [Data Source and Structure](#data-source-and-structure)  
4. [Tools and Technologies](#tools-and-technologies)  
5. [Methodology](#methodology)  
6. [Dashboard Overview](#dashboard-overview)  
7. [Key Insights and Visual Analysis](#key-insights-and-visual-analysis)  
   - Top 10 Keywords by Search Volume  
   - Number of Keywords Each Bank Ranks For  
   - Keyword Visibility Share (%) per Bank  
   - SEO Visibility vs Revenue Correlation  
8. [Key Takeaways](#key-takeaways)
9. [Recommendations](#recommendations)  
10. [Limitations](#limitations)  
11. [Future Enhancements](#future-enhancements)  
12. [Project Links](#project-links)  
13. [About the Author](#about-the-author)  

---

## Overview
This project presents an end-to-end *SEO visibility and keyword performance analysis* of selected Nigerian banks within the consumer banking sector.  
It showcases practical experience in *data collection, Python-based data cleaning, metric creation, and interactive dashboard development using Power BI*.

The analysis focuses on uncovering:
- Which banks dominate search engine visibility
- How keyword coverage varies across banks
- Whether SEO visibility correlates with bank revenue

---

## Business Objective
The objective of this project is to evaluate the *SEO performance of Nigerian consumer banks, identify visibility leaders, and assess the relationship between **search visibility and financial performance*.

This analysis is positioned from a *marketing and business intelligence perspective*, emphasizing actionable insights rather than raw keyword counts.

---

## Data Source and Structure

### Data Collection
Keyword data was generated using *WordStream Free Keyword Tool*.  
For each of the 10 selected banks, consumer banking-related keywords were researched and exported as individual CSV files.

### Original Dataset Columns
Each bank’s dataset initially contained the following fields:
- Keyword Text  
- Competition  
- Competition Index  
- Search Volume  
- Low Top of Page Bid  
- High Top of Page Bid  

### Data Reduction and Final Structure
To ensure analytical relevance:
- Bid-related and index columns were dropped.
- Bank names were standardized.
- Keywords were cleaned and merged into a unified dataset.

The final analytical dataset contains:
- Bank  
- Keyword  
- Search Volume  
- Competition  
- SEO Visibility Score  
- Bank Revenue  

---

## Tools and Technologies
- *Python (Jupyter Notebook)* – Data cleaning, transformation, and merging  
- *Pandas* – Data manipulation and aggregation  
- *Power BI* – Interactive dashboard and data visualization  
- *WordStream* – Keyword research  
- *CSV / Excel* – Data storage and integration  

---

## Methodology

### Data Preparation
- Combined 10 individual bank keyword datasets into one consolidated table.
- Removed irrelevant columns to reduce noise.
- Standardized text fields for consistency.

### SEO Visibility Metric
A custom *SEO Visibility Score* was designed to quantify digital presence:

> *SEO Visibility Score = Total Keyword Count per Bank × Total Search Volume per Bank*

This metric reflects both *keyword coverage* and *search demand*.

### Revenue Integration
Publicly available bank revenue figures were added to assess correlation with SEO visibility.

---

## Dashboard Overview
The Power BI dashboard provides a consolidated view of:
- High-demand consumer banking keywords
- Keyword ranking coverage by bank
- SEO visibility dominance
- Relationship between SEO visibility and revenue
  
   ![Dashboard](https://github.com/AnimashaunRoheemot/SEO-Visibility-Analysis-Of-Nigeria-Banks-/blob/main/Screenshot%20(342).png) 

---

## Key Insights and Visual Analysis

### 1. Top 10 Keywords by Search Volume
The most searched keywords are heavily centered around *digital and online banking services*, indicating strong consumer demand for digital banking solutions.

![Top 10 keywords](https://github.com/)  

---

### 2. Number of Keywords Each Bank Ranks For
- *Zenith Bank* ranks for the highest number of keywords.
- *Ecobank* and *Access Bank* closely follow.
- Smaller banks show significantly lower keyword coverage.

![Number of Keywords Each Bank Ranks For](https://github.com/)

---

### 3. Keyword Visibility Share (%) per Bank
SEO visibility is highly concentrated among a few dominant banks.
- *Zenith Bank* leads in overall visibility share.
- Banks with lower keyword reach show reduced digital presence.
- 
![Keyword Visibility Share (%) per Bank](https://github.com/) 

---

### 4. SEO Visibility vs Revenue Correlation
The correlation analysis suggests a *positive relationship* between SEO visibility and bank revenue.  
Banks with stronger search presence tend to report higher revenue figures.

 ![SEO Visibility vs Revenue Correlation](https://github.com/) 

---

## Key Takeaways
- SEO visibility within Nigerian consumer banking is dominated by a few major players.
- Keyword visibility share provides deeper insight than keyword count alone.
- Strong SEO performance appears to align with higher revenue levels.

---

## Recommendations
- Invest in SEO-driven content focused on high-intent banking keywords.
- Optimize digital platforms for mobile and search performance.
- Monitor SEO performance continuously using BI dashboards.
- Smaller banks should target niche keywords to improve visibility.

---

## Limitations
- Keyword data was sourced from free SEO tools.
- Revenue figures are based on publicly available information.
- The SEO visibility score is a derived metric and excludes backlink authority.

---

## Future Enhancements
- Include keyword ranking positions.
- Integrate paid SEO tool data.
- Perform time-series SEO trend analysis.
- Expand to content and backlink performance metrics.

---

## Project Links
- *Cleaned Excel file link :* https://docs.google.com/spreadsheets/d/1PPYFhqNNWuD8v1rk1WBpCt903fBVQi0z/edit?usp=sharing&ouid=108207302004017690777&rtpof=true&sd=true.
- 🔗 *Interactive Power BI Dashboard:* https://app.powerbi.com/view?r=eyJrIjoiYmQzYjViY2YtZWJjOS00YWJmLTliOTEtN2Q2NGJiNDc4ZDQzIiwidCI6ImJlMTBmNThhLTI5MzktNGE0Zi1hZWE0LWI0ZjVhM2JkZmVkZSJ9.
- 📄 *PDF Report:* https://drive.google.com/file/d/1f428IjTo-WrlzOQfHKVaWm_UnRPGaF0J/view?usp=sharing.

---

## About the Author
*Animashaun Roheemot*  
Data Analyst with a focus on *Business Intelligence, SEO Analytics, and Data Visualization*.  
Skilled in transforming raw data into actionable insights using *Excel,Sql,Google sheet,Python and Power BI*.
