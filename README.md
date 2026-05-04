# 🐢 TurtleCo Financial Dashboard

> **Tableau-powered Profit & Loss analytics for TurtleCo — covering FY2018 to FY2020**

---

## 📊 Project Overview

This Tableau workbook provides a comprehensive financial reporting suite for **TurtleCo**, built around the company's Profit & Loss statement for the fiscal years **2018, 2019, and 2020**. It consolidates trading, operating, non-operating, and balance sheet data into an interactive, filter-driven dashboard experience.

The dashboard is scoped to **Australia** across the **Europe, North America, and Oceania** regions, covering all four quarters and all 12 months of each fiscal year.

---

## 📁 Dashboard Views

| Sheet | Description |
|-------|-------------|
| **Profit & Loss Statement** | Full P&L breakdown by Year → Class → Sub-class → Account |
| **Gross Profit** | Annual gross profit trend (2018–2020) |
| **EBITDA** | Earnings before interest, tax, depreciation & amortisation |
| **Operating Profit** | Trading + Operating account combined |
| **PBIT** | Profit before interest and tax |
| **Net Profit** | Bottom-line profit after all deductions |
| **Sales \| Gross Profit \| Net Profit** | Monthly trend lines segmented by year and quarter |
| **Gross Profit \| EBITDA \| Operating Profit** | Monthly performance comparison across three profitability metrics |
| **Sales \| Marketing Expense** | Marketing spend vs. revenue over time |
| **Sales \| GP Margin \| NP Margin** | Revenue alongside gross and net profit margin trends |

---

## 📈 Key Financial Metrics (Australia)

| Metric | 2018 | 2019 | 2020 |
|---|---|---|---|
| **Sales** | 4,02,458 | 6,26,700 | 9,86,109 |
| **Gross Profit** | 2,33,652 | 3,20,088 | 4,63,351 |
| **Gross Profit Margin** | 58.06% | 51.08% | 46.99% |
| **EBITDA** | 74,183 | 13,684 | -65,780 |
| **Operating Profit** | 30,083 | -46,616 | -1,59,308 |
| **PBIT** | 34,048 | -41,646 | -1,50,281 |
| **Net Profit** | 17,921 | -67,200 | -1,89,659 |
| **Net Profit Margin** | 4.45% | -10.72% | -19.23% |
| **Marketing Expense** | -47,256 | -97,932 | -1,73,339 |

> ⚠️ **Trend Alert**: While sales grew consistently year-over-year, profitability declined sharply — the company moved from a net profit in 2018 to a significant net loss by 2020, driven by rapidly rising operating and marketing expenses.

---

## 🗂️ Data Structure

### P&L Classes

```
├── Trading Account
│   ├── Sales
│   ├── Sales Return
│   └── Cost of Sales
│
├── Operating Account
│   ├── Operating Expenses
│   │   ├── Administration (Entertainment, Office Supplies, Other, Professional Services, Telephone, Travel, Utilities)
│   │   └── Marketing (Advertisements, Commissions)
│   ├── Sales & Distribution (Staff Costs)
│   └── Depreciation & Amortisation (Equipment, Intangible Assets)
│
├── Non-Operating
│   ├── Dividend Income
│   ├── Exchange Loss/Gain
│   ├── Gain/Loss on Sales of Asset
│   └── Interest Income
│
└── Interest & Tax
    ├── Interest Expense
    └── Taxation
```

### Balance Sheet Classes

```
├── Assets
│   ├── Current Assets (Cash & Cash Equivalents, Inventory, Investments, Receivables)
│   └── Non-Current Assets (Intangible Assets, Property Plant & Equipment)
│
└── Liabilities and Owners' Equity
    ├── Current Liabilities (Other Payables, Trade Payables)
    ├── Long-Term Liabilities (Long Term Obligations)
    └── Owners' Equity
        ├── Retained Earnings (Dividends Paid, Retained Earnings)
        └── Share Capital
```

---

## 🔍 Dashboard Filters

The workbook supports the following interactive filters:

- **Country** — Australia, Canada, France, Germany
- **Region** — Europe, North America, Oceania
- **Quarter** — Qtr1, Qtr2, Qtr3, Qtr4
- **Month** — All 12 months
- **Report** — Adjusting, Balance Sheet, Profit and Loss

---

## 🛠️ Built With

- [Tableau Desktop / Tableau Public](https://www.tableau.com/)
- Financial data structured for multi-year P&L and Balance Sheet reporting
- Dimensions: Calendar Year, Quarter, Month, Country, Region, Account Hierarchy

---

## 🚀 Getting Started

1. **Clone or download** this repository.
2. Open the `.twbx` (Tableau Packaged Workbook) file in **Tableau Desktop** or upload it to **Tableau Public/Server**.
3. Use the filter panel to explore data by country, region, quarter, and month.
4. Navigate between sheets using the dashboard tabs.

---

## 📌 Notes

- All monetary values are in the **local currency** of the reporting entity.
- The **Adjusting** class captures year-end adjustment entries.
- Negative values represent expenses, losses, or outflows as per standard accounting convention.
- Data is scoped to **Australia** as the primary country filter in most views.

---

## 📄 License

This project is for internal financial reporting and analysis purposes. Please refer to your organisation's data governance policy before sharing externally.

---

*TurtleCo · Profit & Loss Statement · For the year ending 31 December 2020*
