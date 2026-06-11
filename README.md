# FinancialReporting — TurtleCo P&L Dashboard

A Tableau dashboard that delivers a full Profit & Loss reporting suite
for TurtleCo across FY2018–2020 — tracking sales growth, margin
compression, and profitability decline across regions and quarters.

## Business Problem

Finance and management teams need a fast, visual way to review P&L
performance across multiple years, regions, and account hierarchies.
Static spreadsheet reports make it hard to spot trends or drill into
specific quarters, expense categories, or margin movements.
This project builds an interactive Tableau workbook that consolidates
trading, operating, non-operating, and balance sheet data into a
single filter-driven dashboard experience.

## Data

Financial data for TurtleCo covering FY2018, FY2019, and FY2020:

| Table              | Description                                              |
| ------------------ | -------------------------------------------------------- |
| P&L Data           | Trading, Operating, Non-Operating, Interest & Tax classes |
| Balance Sheet Data | Assets, Liabilities, and Owners' Equity                  |
| Dimensions         | Year, Quarter, Month, Country, Region, Account Hierarchy |

Scoped to Australia across Europe, North America, and Oceania regions,
covering all four quarters and all 12 months of each fiscal year.
Countries available: Australia, Canada, France, Germany.

## Approach

1. **Data prep** — Excel: structured by P&L class hierarchy
(Class → Sub-Class → Account) with calendar dimensions added
2. **Dashboard views** — 10 Tableau sheets built across two pages:
   - `Profit & Loss Statement` — full P&L breakdown with drill-down
   - `Gross Profit` — annual gross profit trend (2018–2020)
   - `EBITDA` — earnings before interest, tax, depreciation & amortisation
   - `Operating Profit` — trading + operating account combined
   - `PBIT` — profit before interest and tax
   - `Net Profit` — bottom-line profit after all deductions
   - `Sales | Gross Profit | Net Profit` — monthly trend lines by year and quarter
   - `Gross Profit | EBITDA | Operating Profit` — monthly profitability comparison
   - `Sales | Marketing Expense` — marketing spend vs. revenue over time
   - `Sales | GP Margin | NP Margin` — revenue alongside margin trends
3. **Filters** — Country, Region, Quarter, Month, Report type
(Adjusting / Balance Sheet / Profit and Loss)

## Key Findings

| Metric               | 2018     | 2019      | 2020       |
| -------------------- | -------- | --------- | ---------- |
| Sales                | 4,02,458 | 6,26,700  | 9,86,109   |
| Gross Profit         | 2,33,652 | 3,20,088  | 4,63,351   |
| Gross Profit Margin  | 58.06%   | 51.08%    | 46.99%     |
| EBITDA               | 74,183   | 13,684    | -65,780    |
| Operating Profit     | 30,083   | -46,616   | -1,59,308  |
| Net Profit           | 17,921   | -67,200   | -1,89,659  |
| Net Profit Margin    | 4.45%    | -10.72%   | -19.23%    |
| Marketing Expense    | -47,256  | -97,932   | -1,73,339  |

- **Sales grew 145%** from FY2018 to FY2020 — but profitability collapsed
- **Net profit flipped to a loss** by FY2019 and deepened to -1,89,659 in FY2020
- **Gross profit margin eroded** from 58% to 47% over three years
- **Marketing expense tripled** (47K → 1,73,339) — the single biggest driver of loss
- **EBITDA went negative** in FY2020, signalling operating cost growth outpacing revenue

## Tools

Tableau Desktop · Excel

## Dashboard

[📄 View Full Dashboard (PDF)](https://github.com/Madhushree-Majumder/Financial-Reporting-and-Financial-Analysis-Using-Tableau/blob/main/TABLEAU%20FINANCE.pdf)
