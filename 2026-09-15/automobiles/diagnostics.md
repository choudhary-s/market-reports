# Daily Market Intelligence Report — Diagnostics

Report period: **2026-09-15**

## Data Availability

| Dataset | Status | Provider Used | Impact |
|---|---|---|---|
| market_dashboard:NIFTYAUTO:breadth | Available | nse | None |
| market_dashboard:NIFTYAUTO:day | Available | yfinance | None |
| market_dashboard:NIFTYAUTO:history | Available | nse | None |
| market_dashboard:NIFTYAUTO:prior | Available | nse | None |
| market_dashboard:NIFTYAUTO:valuation_3y | Available | niftyindices | None |
| market_dashboard:NIFTYEVNEWAGEAUTOMOTIVE:breadth | Available | nse | None |
| market_dashboard:NIFTYEVNEWAGEAUTOMOTIVE:day | Available | nse | None |
| market_dashboard:NIFTYEVNEWAGEAUTOMOTIVE:history | Unavailable | - | BSE fallback currently supplies SENSEX only. |
| market_dashboard:NIFTYEVNEWAGEAUTOMOTIVE:prior | Available | nse | None |
| market_dashboard:NIFTYEVNEWAGEAUTOMOTIVE:valuation_3y | Available | niftyindices | None |

<details><summary>Provider attempt detail</summary>

- **market_dashboard:NIFTYAUTO:breadth**: -
- **market_dashboard:NIFTYAUTO:day**: india_funds: NIFTYAUTO is not a configured India fund instrument
- **market_dashboard:NIFTYAUTO:history**: india_funds: NIFTYAUTO is not a configured India fund instrument; yfinance: Rejected incomplete price history: history has 3 consecutive missing trading sessions from 2026-07-20 through 2026-07-22
- **market_dashboard:NIFTYAUTO:prior**: india_funds: NIFTYAUTO is not a configured India fund instrument; yfinance: Fetched 1 rows for ^CNXAUTO but none fall in the requested range 2026-09-11..2026-09-11 -- check it isn't a weekend/holiday or a future date
- **market_dashboard:NIFTYAUTO:valuation_3y**: nse: NSE returned no valuation rows for NIFTY AUTO in 2023-09-01..2026-09-15
- **market_dashboard:NIFTYEVNEWAGEAUTOMOTIVE:breadth**: -
- **market_dashboard:NIFTYEVNEWAGEAUTOMOTIVE:day**: india_funds: NIFTYEVNEWAGEAUTOMOTIVE is not a configured India fund instrument; yfinance: No verified Yahoo Finance symbol is configured for NIFTYEVNEWAGEAUTOMOTIVE
- **market_dashboard:NIFTYEVNEWAGEAUTOMOTIVE:history**: india_funds: NIFTYEVNEWAGEAUTOMOTIVE is not a configured India fund instrument; yfinance: No verified Yahoo Finance symbol is configured for NIFTYEVNEWAGEAUTOMOTIVE; nse: Rejected incomplete price history: history begins at 2024-12-16, too late for requested start 2022-09-01; bse: NIFTYEVNEWAGEAUTOMOTIVE is not a supported BSE index in this provider
- **market_dashboard:NIFTYEVNEWAGEAUTOMOTIVE:prior**: india_funds: NIFTYEVNEWAGEAUTOMOTIVE is not a configured India fund instrument; yfinance: No verified Yahoo Finance symbol is configured for NIFTYEVNEWAGEAUTOMOTIVE
- **market_dashboard:NIFTYEVNEWAGEAUTOMOTIVE:valuation_3y**: nse: NSE returned no valuation rows for NIFTY EV & NEW AGE AUTOMOTIVE in 2023-09-01..2026-09-15

</details>
