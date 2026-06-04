# Bsc-data-analytics-internship
Collection of campaign analytics, automation, reporting and customer engagement projects completed during my internship at Bombay Shaving Company.


# PROJECT-1 CRM Campaign Reporting Automation

## Overview

Python-based automation tool developed during my internship at Bombay Shaving Company to automate CRM campaign reporting and Google Sheets updates.

## Key Features

- Multi-brand support (Durex, Avon, Enamor, Neurogum)
- Automated KPI calculations
- Google Sheets integration
- Single UTM processing
- Bulk UTM processing
- Automated reporting workflow

## Tech Stack

- Python
- Pandas
- Tkinter
- GSpread
- Google Sheets API

## Metrics Generated

- Delivery Rate
- Open Rate
- Click Rate
- CTOR
- CVR
- ROAS
- AOV
- Revenue
- Orders
- Sessions

## Business Impact

- Reduced reporting effort from hours to minutes
- Improved reporting accuracy
- Standardized CRM reporting process
- Reduced manual intervention

## Files

- CRM_Campaign_Reporting_Automation.ipynb



# Project 2 - MTD CRM Performance Reporting Automation

## Overview

Developed a Python-based automation system to streamline Month-To-Date (MTD) CRM performance reporting across multiple brands. The solution automates revenue, spend, ROAS, target achievement, and historical performance tracking while updating centralized Google Sheets in real time.

## Business Problem

- MTD reporting was performed manually using multiple data sources.
- Revenue and spend data had to be consolidated separately.
- Reporting required approximately 1 hour of manual effort daily.
- High probability of calculation and reporting errors.
- Limited visibility into real-time CRM performance.

## Solution

Built a GUI-based automation tool using Python that:

- Processes revenue data from Gokwik exports.
- Fetches spends from Google Sheets.
- Calculates MTD achievement metrics automatically.
- Updates centralized reporting sheets.
- Maintains historical month-wise reporting.
- Supports multiple brands through a scalable framework.

## Key Features

- Automated MTD revenue reporting.
- Automated spend aggregation.
- ROAS calculation.
- Target vs achievement tracking.
- Historical performance comparison.
- Dynamic Google Sheet updates.
- User-friendly GUI interface.
- Multi-brand support.

## Brand Coverage

### Durex

- Dedicated automation workflow.
- Advanced UTM classification logic.
- Coupon-based revenue attribution.
- Separate spend sheet integration.
- Custom reporting structure.

### Avon, Enamor & Neurogum

- Shared automation framework.
- Standardized revenue processing.
- Automated spend integration.
- Unified reporting workflow.

## Tech Stack

- Python
- Pandas
- Tkinter
- GSpread
- Google Sheets API

## Business Impact

- Reduced reporting effort from ~1 hour to less than 1 minute.
- Eliminated manual calculation errors.
- Enabled real-time MTD performance visibility.
- Standardized reporting across brands.
- Improved operational efficiency and decision-making.

## Files

- CRM_MTD_Performance_Reporting_Durex.ipynb
- CRM_MTD_Performance_Reporting_Avon,Enamor,Neurogum_Brands.ipynb


# Project 3 - Flow Analytics Automation

## Overview

Developed a Python-based automation system to track and analyze CRM flow performance across multiple brands. The solution consolidates engagement, session, order, and revenue data from multiple sources and automatically updates centralized Google Sheets for reporting and performance monitoring.

## Business Problem

* Multiple CRM flows were running simultaneously across brands.
* Flow performance tracking required manual consolidation from different source files.
* Sessions, orders, revenue, and engagement metrics had to be calculated separately.
* Reporting was time-consuming and prone to manual errors.
* Tracking performance across different date ranges lacked flexibility.

## Solution

Built a GUI-based automation tool using Python that:

* Processes engagement data from KwikEngage/Tellephant exports.
* Maps flows using a centralized Flow Mapping Sheet.
* Calculates engagement, traffic, and conversion metrics automatically.
* Supports flexible date-range reporting.
* Updates Google Sheets dashboards automatically.
* Tracks Meta template category changes through Gmail integration.

## Key Features

* Multi-brand support (Durex, Avon, Enamor, Neurogum)
* Flexible date-range reporting
* Automated flow mapping
* Engagement metrics automation
* Session tracking
* Order and revenue attribution
* Google Sheets integration
* Gmail integration for Meta alerts
* Marketing vs Utility flow classification
* Automated KPI calculations

## Metrics Generated

### Engagement Metrics

* Total Sent
* Delivered
* Delivery Rate
* Opens
* Open Rate
* Clicks
* Click Rate

### Traffic Metrics

* Sessions

### Conversion Metrics

* Orders
* Revenue

### Business Metrics

* CVR
* AOV
* ROAS

### Monitoring Metrics

* Meta Template Category Alerts

## Tech Stack

* Python
* Pandas
* NumPy
* Tkinter
* GSpread
* Google Sheets API
* Gmail API

## Business Impact

* Eliminated manual flow reporting effort.
* Standardized flow performance tracking across brands.
* Reduced reporting errors and inconsistencies.
* Enabled flexible reporting for any date range.
* Automated KPI generation and dashboard updates.
* Improved visibility into CRM flow performance.
* Introduced proactive monitoring of Meta template category changes.

## Files

* Flow_Analytics_Automation.ipynb


# Project 4 - CRM Send-Time Optimization Heatmap

## Overview

Developed a data-driven CRM send-time optimization framework to identify high-performing campaign delivery windows across multiple brands. The project analyzed historical CRM campaign performance data to determine the optimal day and time combinations that maximize Click-Through Rate (CTR) and improve overall engagement.

## Business Problem

* CRM campaigns were scheduled primarily based on intuition and historical practices.
* No structured methodology existed to determine optimal send times.
* High-intent engagement windows remained unidentified.
* Campaign performance varied significantly across brands and time slots.
* Suboptimal scheduling resulted in lower engagement and CTR.

## Solution

Built an analytical framework that:

* Processed historical CRM campaign performance data.
* Evaluated campaigns using CTR as the primary optimization metric.
* Created Day × Time Slot performance heatmaps.
* Compared performance patterns across brands.
* Identified high-intent engagement windows.
* Generated brand-specific scheduling recommendations.

## Key Features

* Historical campaign performance analysis.
* Day-wise performance evaluation.
* Time-slot level CTR analysis.
* Brand-specific optimization insights.
* Performance normalization across campaigns.
* Heatmap-based visualization.
* Send-time recommendation framework.
* Cross-brand comparative analysis.

## Brands Analyzed

* Avon
* Durex
* Neurogum
* Enamor

## Analysis Framework

### Funnel Evaluation

Campaign performance was evaluated across:

* Sent
* Delivered
* Open
* CTR
* CVR

### Optimization Metric

Primary metric used:

* Click Through Rate (CTR)

Secondary metrics considered:

* Open Rate
* Conversion Rate (CVR)
* Delivery Performance

## Key Insights

### Avon

* Peak engagement observed during Monday evening campaigns.
* Weekend campaigns demonstrated stronger performance.
* Higher purchase intent identified during evening slots.

### Durex

* Evening campaigns consistently outperformed other time windows.
* Sunday evenings generated the highest CTR.
* Clear late-day engagement behavior observed.

### Neurogum

* Afternoon campaigns delivered the most consistent performance.
* Friday afternoon emerged as the strongest engagement period.
* Stable weekday engagement trend identified.

### Enamor

* Early-week morning campaigns showed the strongest results.
* Midweek engagement remained stable.
* Recovery trend observed toward Friday.

## Business Impact

* Shifted campaign planning from intuition to data-driven scheduling.
* Improved CTR through optimized send-time selection.
* Increased campaign efficiency without additional marketing spend.
* Enabled brand-specific CRM execution strategies.
* Improved decision-making through measurable performance insights.

## Tech Stack

* Python
* Pandas
* NumPy
* Matplotlib
* Seaborn
* Excel
* Google Sheets

## Strategic Outcome

The project established a repeatable framework for CRM send-time optimization, enabling brands to schedule campaigns during high-intent engagement windows and consistently improve user interaction rates through data-backed decision making.

## Files

* Durex_Heatmap_Code.ipynb
* Neurogum_Heatmap_Code.ipynb
* Avon_Heatmap_Code.ipynb
* Enamor_Heatmap_Code.ipynb


