# Daily Market Intelligence Report — Diagnostics

Report period: **2026-09-15**

## Data Availability

| Dataset | Status | Provider Used | Impact |
|---|---|---|---|
| market_dashboard:NIFTYFINANCIALSERVICES:breadth | Available | nse | None |
| market_dashboard:NIFTYFINANCIALSERVICES:day | Available | yfinance | None |
| market_dashboard:NIFTYFINANCIALSERVICES:history | Available | nse | None |
| market_dashboard:NIFTYFINANCIALSERVICES:prior | Available | nse | None |
| market_dashboard:NIFTYFINANCIALSERVICES:valuation_3y | Available | niftyindices | None |
| market_dashboard:NIFTYFINANCIALSERVICESEXBANK:breadth | Available | nse | None |
| market_dashboard:NIFTYFINANCIALSERVICESEXBANK:day | Available | nse | None |
| market_dashboard:NIFTYFINANCIALSERVICESEXBANK:history | Unavailable | - | BSE fallback currently supplies SENSEX only. |
| market_dashboard:NIFTYFINANCIALSERVICESEXBANK:prior | Available | nse | None |
| market_dashboard:NIFTYFINANCIALSERVICESEXBANK:valuation_3y | Available | niftyindices | None |
| market_dashboard:NIFTYMIDSMALLFINANCIALSERVICES:breadth | Available | nse | None |
| market_dashboard:NIFTYMIDSMALLFINANCIALSERVICES:day | Available | nse | None |
| market_dashboard:NIFTYMIDSMALLFINANCIALSERVICES:history | Unavailable | - | BSE fallback currently supplies SENSEX only. |
| market_dashboard:NIFTYMIDSMALLFINANCIALSERVICES:prior | Available | nse | None |
| market_dashboard:NIFTYMIDSMALLFINANCIALSERVICES:valuation_3y | Available | niftyindices | None |

<details><summary>Provider attempt detail</summary>

- **market_dashboard:NIFTYFINANCIALSERVICES:breadth**: -
- **market_dashboard:NIFTYFINANCIALSERVICES:day**: india_funds: NIFTYFINANCIALSERVICES is not a configured India fund instrument
- **market_dashboard:NIFTYFINANCIALSERVICES:history**: india_funds: NIFTYFINANCIALSERVICES is not a configured India fund instrument; yfinance: Rejected incomplete price history: history has 3 consecutive missing trading sessions from 2026-07-20 through 2026-07-22
- **market_dashboard:NIFTYFINANCIALSERVICES:prior**: india_funds: NIFTYFINANCIALSERVICES is not a configured India fund instrument; yfinance: Fetched 1 rows for NIFTY_FIN_SERVICE.NS but none fall in the requested range 2026-09-11..2026-09-11 -- check it isn't a weekend/holiday or a future date
- **market_dashboard:NIFTYFINANCIALSERVICES:valuation_3y**: nse: NSE returned no valuation rows for NIFTY FINANCIAL SERVICES in 2023-09-01..2026-09-15
- **market_dashboard:NIFTYFINANCIALSERVICESEXBANK:breadth**: -
- **market_dashboard:NIFTYFINANCIALSERVICESEXBANK:day**: india_funds: NIFTYFINANCIALSERVICESEXBANK is not a configured India fund instrument; yfinance: No verified Yahoo Finance symbol is configured for NIFTYFINANCIALSERVICESEXBANK
- **market_dashboard:NIFTYFINANCIALSERVICESEXBANK:history**: india_funds: NIFTYFINANCIALSERVICESEXBANK is not a configured India fund instrument; yfinance: No verified Yahoo Finance symbol is configured for NIFTYFINANCIALSERVICESEXBANK; nse: Rejected incomplete price history: history begins at 2024-12-16, too late for requested start 2022-09-01; bse: NIFTYFINANCIALSERVICESEXBANK is not a supported BSE index in this provider
- **market_dashboard:NIFTYFINANCIALSERVICESEXBANK:prior**: india_funds: NIFTYFINANCIALSERVICESEXBANK is not a configured India fund instrument; yfinance: No verified Yahoo Finance symbol is configured for NIFTYFINANCIALSERVICESEXBANK
- **market_dashboard:NIFTYFINANCIALSERVICESEXBANK:valuation_3y**: nse: NSE returned no valuation rows for NIFTY FINANCIAL SERVICES EX-BANK in 2023-09-01..2026-09-15
- **market_dashboard:NIFTYMIDSMALLFINANCIALSERVICES:breadth**: -
- **market_dashboard:NIFTYMIDSMALLFINANCIALSERVICES:day**: india_funds: NIFTYMIDSMALLFINANCIALSERVICES is not a configured India fund instrument; yfinance: No verified Yahoo Finance symbol is configured for NIFTYMIDSMALLFINANCIALSERVICES
- **market_dashboard:NIFTYMIDSMALLFINANCIALSERVICES:history**: india_funds: NIFTYMIDSMALLFINANCIALSERVICES is not a configured India fund instrument; yfinance: No verified Yahoo Finance symbol is configured for NIFTYMIDSMALLFINANCIALSERVICES; nse: Rejected incomplete price history: history begins at 2024-12-16, too late for requested start 2022-09-01; bse: NIFTYMIDSMALLFINANCIALSERVICES is not a supported BSE index in this provider
- **market_dashboard:NIFTYMIDSMALLFINANCIALSERVICES:prior**: india_funds: NIFTYMIDSMALLFINANCIALSERVICES is not a configured India fund instrument; yfinance: No verified Yahoo Finance symbol is configured for NIFTYMIDSMALLFINANCIALSERVICES
- **market_dashboard:NIFTYMIDSMALLFINANCIALSERVICES:valuation_3y**: nse: NSE returned no valuation rows for NIFTY MIDSMALL FINANCIAL SERVICES in 2023-09-01..2026-09-15

</details>
