
# 📐 DAX Measures Documentation

This document explains the DAX measures used in the Meta Ads Performance Dashboard.

---

## 1. Impressions

### Purpose

Calculates the total number of ad impressions.

### Formula

```DAX
Impressions = COUNTROWS(...)

2. Clicks
Purpose

Calculates total clicks.

Formula
Clicks = COUNTROWS(...)
Business Value

Measures audience interaction.

3. CTR (Click Through Rate)
Purpose

Measures how many users clicked after seeing an advertisement.

Formula
CTR = DIVIDE([Clicks],[Impressions],0)
Business Value

Higher CTR indicates better advertisement performance.

4. CPC (Cost Per Click)
Purpose

Calculates advertising cost for each click.

Formula
CPC = DIVIDE([Spend],[Clicks],0)
Business Value

Lower CPC indicates more efficient advertising.

5. Conversion Rate
Purpose

Measures percentage of visitors who completed a desired action.

Formula
Conversion Rate = DIVIDE([Conversions],[Clicks],0)
Business Value

Evaluates campaign effectiveness.

6. ROAS
Purpose

Return On Advertising Spend.

Formula
ROAS = DIVIDE([Revenue],[Spend],0)
Business Value

Measures profitability of advertising campaigns.


Continue this format for all your measures.

---

# 3️⃣ Update `Documentation/Dashboard_Report.md`

Replace the basic report with a professional report.

```markdown
# 📊 Dashboard Report

## Project Objective

The objective of this dashboard is to analyze Meta (Facebook & Instagram) advertising campaigns and provide interactive insights for campaign optimization.

---

# Dashboard Features

- Interactive KPI Cards
- Campaign Filters
- Audience Analysis
- Geographic Analysis
- Monthly Trends
- CTR Analysis
- Engagement Analysis
- Budget Monitoring

---

# Data Model

The dashboard follows a star-schema model consisting of:

- Campaign Table
- Calendar Table
- Ad Events Table

Relationships were created to support time intelligence and filtering.

---

# Data Preparation

Power Query was used to:

- Clean data
- Remove duplicates
- Handle missing values
- Create calculated columns
- Standardize formats

---

# DAX Measures

Key measures include:

- Impressions
- Clicks
- CTR
- CPC
- Conversion Rate
- Spend
- Revenue
- ROAS

---

# Business Insights

The dashboard helps identify:

- Best performing campaigns
- Audience engagement
- Geographic trends
- Budget utilization
- Marketing effectiveness

---

# Business Recommendations

- Increase budget for high-performing campaigns.
- Optimize low CTR advertisements.
- Monitor engagement trends regularly.
- Improve underperforming audience segments.

---

# Future Improvements

- Real-time Meta Ads integration
- Predictive analytics
- Machine Learning forecasting
- Executive KPI dashboard