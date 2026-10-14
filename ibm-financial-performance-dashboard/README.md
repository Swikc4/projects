# IBM Financial Performance Dashboard (2023–2025)

A Tableau Public dashboard exploring IBM's revenue, profitability, operating cash flow, and business segment performance using three years of financial data.

## Dashboard overview

The dashboard includes four 2025 KPI summaries and five Tableau visualizations:

- Annual revenue trend (2023–2025)
- Revenue by business segment (2025)
- Net income trend (2023–2025)
- Gross profit trend (2023–2025)
- Operating cash flow trend (2023–2025)

## Key metrics

All values are in USD billions, rounded to two decimal places.

| Metric | 2023 | 2024 | 2025 |
| --- | ---: | ---: | ---: |
| Revenue | 61.86 | 62.75 | 67.54 |
| Gross profit | 34.30 | 35.55 | 39.30 |
| Net income | 7.50 | 6.02 | 10.59 |
| Operating cash flow | 13.93 | 13.45 | 13.19 |

### 2025 segment revenue

| Segment | Revenue (USD billions) |
| --- | ---: |
| Software | 29.96 |
| Consulting | 21.06 |
| Infrastructure | 15.72 |
| Financing | 0.74 |
| Other revenue and reconciliation | 0.06 |

## Key observations

- Revenue and gross profit increased between 2023 and 2025.
- Net income declined in 2024 before recovering in 2025.
- Software was the largest revenue segment in 2025.
- Operating cash flow declined modestly over the period.

## Tools and techniques

**Tools:** Tableau Public and Microsoft Excel.

**Techniques:** Data preparation, data relationships by year, calculated measures converting USD millions to billions, time-series visualization, segment comparison, KPI reporting, and dashboard layout design.

## Files and live dashboard

The project documentation is provided here. The source Excel workbook, Tableau packaged workbook, and demo video are **not yet stored in this GitHub folder**.

To reproduce the dashboard, use the source data's `Annual Financials` and `Segment Revenue` tables, relate them by the `Year` field, and build the five visualizations listed above.

> Portfolio project for analysis and visualization. Financial figures are transcribed from the Tableau project and should be verified against the source workbook before external use.
