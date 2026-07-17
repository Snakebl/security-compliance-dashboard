# Security Compliance Reporting Dashboard — Power BI

## Overview
This project documents the design and delivery of an enterprise security compliance 
dashboard built during my internship at W.R. Grace and Co. (May-August 2025). The dashboard is now the property of W.R. Grace and Co., as such I can only share a written breakdown of my development process and data modeling choices - all of which are entirely transferable and non-confidential. 

The dashboard processed 1,000+ global security incident records to surface KPIs, risk 
trends, and compliance metrics for security leadership, reducing manual reporting 
time by 40%.

## Note on Source Data
All organizational data from W.R. Grace and Co. is confidential and is not included 
in this repository. This README documents the methodology, architecture, and outcomes 
of the project for portfolio purposes only.

## Problem Statement
The security team managed global incident data across multiple regions using manual 
spreadsheet processes that required significant staff time each reporting cycle. 
Leadership lacked real-time visibility into incident trends, risk patterns, and 
regional performance metrics.

## Solution
Designed and delivered an automated Power BI dashboard that:
- Extracted and transformed incident data from Enablon using Power Query
- Built a scalable data model supporting multiple analytical views
- Created dynamic visualizations tracking KPIs, milestone health, and risk trends
- Automated recurring data refresh, eliminating manual compilation

## Technical Architecture

### ETL Pipeline (Power Query)
- Connected to Enablon as the primary data source
- Applied data transformation steps to clean, validate, and structure raw records
- Built reusable query functions for recurring data loads
- Implemented error handling for missing or malformed records

### Data Model (Power BI)
- Designed a star schema supporting incident, region, time, and category dimensions
- Used DAX measures for KPI calculations including incident rate, resolution time, 
  and trend variance
- Optimized relationships for report performance across 1,000+ records

### Dashboard Views
- Executive summary: high-level KPI cards and regional heat map
- Trend analysis: time-series incident volume and severity tracking
- Compliance metrics: control gap indicators and remediation status
- Regional drill-down: per-site incident breakdown with filter controls

## Outcomes
- Reduced manual reporting time by approximately 40%
- Enabled real-time risk visibility for the Security Systems Manager and Director
- Supported weekly stakeholder briefings with consistent, audit-ready data outputs
- Improved cross-regional communication through standardized metric definitions

## Tools and Technologies
- Power BI Desktop
- Power Query (M Language)
- DAX (Data Analysis Expressions)
- Microsoft Excel
- Enablon (source system)
- Microsoft 365

## Skills Demonstrated
ETL pipeline development, data modeling, KPI development, dashboard design, 
reporting automation, stakeholder requirements gathering, compliance reporting, 
executive communication

## Professional Context
Organization: W.R. Grace and Co., Columbia MD
Role: Global Security Projects Intern (Analyst)
Duration: May 2025 - August 2025
