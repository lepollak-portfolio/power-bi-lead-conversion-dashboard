
# Lead Performance Dashboard | Power BI

**LP Analytics — Turning Data Into Opportunity**

An interactive Power BI executive dashboard analyzing lead acquisition, conversion performance, and outreach effectiveness using a publicly available banking lead dataset.

## Executive Overview

![Lead Performance Executive Overview](images/Lead%20Performance%20Overview.jpg)

### Performance Snapshot

| KPI | Result |
|---|---:|
| Total Leads | 69,713 |
| Total Conversions | 1,020 |
| Conversion Rate | 1.46% |
| Reporting Period | July–September 2016 |

The dashboard provides leadership with a consolidated view of lead performance, highlighting opportunities to improve acquisition strategy, evaluate outreach effectiveness, and prioritize higher-performing lead sources.

---

## Business Problem

Organizations investing in lead acquisition need to understand:

- Which lead sources generate the strongest conversion rates?
- How does conversion performance vary across source categories?
- How do contacted and non-contacted leads compare?
- How does performance change over time?
- Where should leadership focus further analysis and potential resource allocation?

This project demonstrates how business intelligence reporting can translate lead-level data into actionable performance insights.

---

## Dataset

**Source:** Public banking lead dataset from Kaggle.

The dataset contains approximately 69,700 lead records, including:

- Lead acquisition sources and categories
- Customer demographics
- Financial and loan attributes
- Contact status
- Approval outcomes

For this analysis, approved leads are treated as conversions.

**Data Disclosure:** This portfolio project uses publicly available sample data and does not contain confidential employer or customer information.

---

## Technical Implementation

### Tools and Technologies

- **Power BI Desktop** — Interactive reporting and visualization
- **DAX** — Calculated measures and KPI development
- **Power Query** — Data preparation and transformation
- **Data Modeling** — Filtering and analytical structure
- **GitHub** — Project documentation and version control

### DAX Measures

The dashboard includes measures for:

- Total Leads
- Total Conversions
- Conversion Rate
- Contact Rate

Measures support dynamic analysis across reporting periods, lead sources, source categories, and contact status.

---

## Dashboard Features

### Executive KPI Reporting

High-level KPI cards summarize lead volume, conversions, and conversion efficiency.

### Lead Source Performance

Horizontal bar charts compare conversion rates across individual acquisition sources, helping identify differences in lead quality and conversion efficiency.

### Source Category Analysis

Category-level visualizations allow leadership to compare performance across broader acquisition groupings.

### Monthly Conversion Trends

A time-series visualization tracks monthly conversion volume to identify changes in performance throughout the reporting period.

### Contact Strategy Analysis

Interactive slicers allow users to compare contacted and non-contacted lead populations, evaluate conversion differences, and investigate outreach-related performance patterns.

---

## Key Business Insights

- **Overall Conversion Performance:** 1,020 conversions from 69,713 leads, representing a 1.46% conversion rate.

- **Source Performance:** Source S134 achieved a 3.72% conversion rate in the overall view, outperforming several other acquisition sources.

- **Category Performance:** Source Category B recorded a 1.66% conversion rate, the highest among the categories displayed in the overall dashboard.

- **Monthly Conversion Trends:** July recorded 310 conversions, August 364, and September 346, making August the strongest month by conversion volume.

- **Outreach Analysis:** Contact-status filtering supports comparisons between contacted and non-contacted leads. These comparisons identify associations rather than proving that outreach caused conversions.

These findings demonstrate how an executive dashboard can support further investigation of lead acquisition efficiency and outreach strategy.

---

## Interactive Dashboard Views

### All Leads — Executive Overview

![All Leads Executive Overview](images/Lead%20Performance%20Overview.jpg)

Displays overall lead acquisition and conversion performance.

### Contacted Leads

![Contacted Leads Dashboard](images/Contacted%20Lead%20Overview.jpg)

Filters the dashboard to leads marked as contacted, allowing focused analysis of conversion performance within the contacted population.

### Non-Contacted Leads

![Non-Contacted Leads Dashboard](images/Non-Contacted%20Lead%20Overview.jpg)

Filters the dashboard to leads marked as not contacted, providing a comparison population for evaluating conversion patterns.

**Note:** Screenshots demonstrate different interactive filter states. The Power BI project file contains the report used to produce these views.

---

## Business Value

This project demonstrates the ability to:

- Translate business questions into measurable KPIs
- Develop interactive executive reporting in Power BI
- Apply DAX calculations and filter-context logic
- Analyze acquisition-channel and conversion performance
- Communicate analytical findings to business stakeholders
- Design visually consistent, decision-focused reporting

---

## Future Enhancements

Potential future improvements include:

- Predictive conversion modeling
- Lead scoring models
- Additional acquisition cost metrics
- Expanded time-series analysis
- Automated reporting and refresh pipelines

---

## Project Files

- [Mock Leads Data.pbix](Mock%20Leads%20Data.pbix) — Power BI report file
- [train.csv](train.csv) — Source dataset
- [images/](images/) — Executive dashboard screenshots

---

## About the Analyst

**Laura Pollak**

**LP Analytics** | Data Analytics • SQL • Power BI • Business Intelligence

*Turning Data Into Opportunity*
