# Daily Market Intelligence Report — Diagnostics

Report period: **2026-09-15**

## Data Availability

| Dataset | Status | Provider Used | Impact |
|---|---|---|---|
| market_dashboard:NIFTYENERGY:breadth | Available | nse | None |
| market_dashboard:NIFTYENERGY:day | Available | yfinance | None |
| market_dashboard:NIFTYENERGY:history | Available | nse | None |
| market_dashboard:NIFTYENERGY:prior | Available | nse | None |
| market_dashboard:NIFTYENERGY:valuation_3y | Available | niftyindices | None |
| market_dashboard:NIFTYOILANDGAS:breadth | Available | nse | None |
| market_dashboard:NIFTYOILANDGAS:day | Available | nse | None |
| market_dashboard:NIFTYOILANDGAS:history | Unavailable | - | BSE fallback currently supplies SENSEX only. |
| market_dashboard:NIFTYOILANDGAS:prior | Available | nse | None |
| market_dashboard:NIFTYOILANDGAS:valuation_3y | Available | niftyindices | None |

<details><summary>Provider attempt detail</summary>

- **market_dashboard:NIFTYENERGY:breadth**: -
- **market_dashboard:NIFTYENERGY:day**: india_funds: NIFTYENERGY is not a configured India fund instrument
- **market_dashboard:NIFTYENERGY:history**: india_funds: NIFTYENERGY is not a configured India fund instrument; yfinance: Rejected incomplete price history: history has 3 consecutive missing trading sessions from 2026-07-20 through 2026-07-22
- **market_dashboard:NIFTYENERGY:prior**: india_funds: NIFTYENERGY is not a configured India fund instrument; yfinance: Fetched 1 rows for ^CNXENERGY but none fall in the requested range 2026-09-11..2026-09-11 -- check it isn't a weekend/holiday or a future date
- **market_dashboard:NIFTYENERGY:valuation_3y**: nse: NSE returned no valuation rows for NIFTY ENERGY in 2023-09-01..2026-09-15
- **market_dashboard:NIFTYOILANDGAS:breadth**: -
- **market_dashboard:NIFTYOILANDGAS:day**: india_funds: NIFTYOILANDGAS is not a configured India fund instrument; yfinance: No verified Yahoo Finance symbol is configured for NIFTYOILANDGAS
- **market_dashboard:NIFTYOILANDGAS:history**: india_funds: NIFTYOILANDGAS is not a configured India fund instrument; yfinance: No verified Yahoo Finance symbol is configured for NIFTYOILANDGAS; nse: Rejected incomplete price history: history has 3 consecutive missing trading sessions from 2023-05-24 through 2023-05-26; bse: NIFTYOILANDGAS is not a supported BSE index in this provider
- **market_dashboard:NIFTYOILANDGAS:prior**: india_funds: NIFTYOILANDGAS is not a configured India fund instrument; yfinance: No verified Yahoo Finance symbol is configured for NIFTYOILANDGAS
- **market_dashboard:NIFTYOILANDGAS:valuation_3y**: nse: NSE returned no valuation rows for NIFTY OIL & GAS in 2023-09-01..2026-09-15

</details>
