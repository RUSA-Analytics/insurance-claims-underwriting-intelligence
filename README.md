# Insurance Claims & Underwriting Intelligence | RUSA Analytics

**Insurance analytics portfolio · Tableau · Synthetic demonstration data**

A four-dashboard Tableau proof of concept by **RUSA Analytics** showing insurance portfolio monitoring, underwriting risk, claims intelligence, and claims operations. The screenshots below were provided by the dashboard developer.

> **Data disclosure:** All insurance figures shown are synthetic demonstration values, not outcomes from a real insurer or a verified client engagement. KPI calculations, definitions, and units should be independently reconciled before they are cited as validated results.

## Dashboard gallery

### 1. Insurance Portfolio Overview
![Insurance Portfolio Overview](screenshots/01_Insurance_Portfolio_Overview.png)

Tracks gross written premium, earned premium, incurred claims, loss ratio, active policies, renewal rate, product performance, and regional performance.

### 2. Underwriting & Operational Risk Analytics
![Underwriting & Operational Risk Analytics](screenshots/02_Underwriting_Operational_Risk_Analytics.png)

Reviews quote-to-bind conversion, average premium, cancellation rate, exposure, renewal rate, and underwriting risk segments.

### 3. Claims Intelligence
![Claims Intelligence](screenshots/03_Claims_Intelligence.png)

Examines claim counts, paid amounts, outstanding reserves, claim severity, settlement times, claim aging, claim status, and attention queues.

### 4. Risk & Claims Operations
![Risk & Claims Operations](screenshots/04_Risk_Claims_Operations.png)

Explores high-risk flags, SLA breaches, reopened claims, special investigation unit (SIU) referrals, estimated leakage, investigation priorities, and risk indicators.

## Business questions demonstrated

- How do written premiums and incurred claims compare across the portfolio?
- How do retention, exposure, and cancellations differ by risk tier or product?
- Which claim categories, statuses, and aging bands merit operational review?
- How could claims teams prioritize review queues based on defined indicators?

A risk flag or SIU referral is **not evidence of fraud**. This dashboard is illustrative decision support, not an automated claim adjudication or fraud determination system.

## Technologies and design

- **Platform:** Tableau (four connected dashboards)
- **Filters:** Date, claim, country, policy type, product, risk tier, and channel
- **Visuals:** KPI cards, trends, segment bars, tables, scatterplots, and donut charts
- **Data:** Synthetic insurance policy, customer, product, geography, channel, claim, and claim-transaction concepts
- **Modeling consideration:** Policy snapshots and claim/transaction facts have different grains; aggregations must be validated to prevent double-counting

## Repository files

```text
README.md
screenshots/
  01_Insurance_Portfolio_Overview.png
  02_Underwriting_Operational_Risk_Analytics.png
  03_Claims_Intelligence.png
  04_Risk_Claims_Operations.png
```

## Portfolio limitations and publication policy

The screenshots are authentic captures supplied by the Tableau developer. They verify the four dashboard visuals were delivered, **not** that the underlying calculations or interactive features passed QA. The source CSVs and packaged Tableau workbook have not been verified as final handover deliverables. No Tableau workbook, datasets, private business information, or demo video is shared in this public repository.

## About RUSA Analytics

RUSA Analytics builds business intelligence, analytics, and decision-support solutions.

- Website: https://www.rusaanalytics.com
- GitHub: https://github.com/RUSA-Analytics

**RUSA Analytics | AI-Powered Insights. Business-Driven Outcomes.**
