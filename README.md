# equity-research-tata-motors
# Equity Research — Integrated 3-Statement Models & Valuation

Independent equity research on Indian listed companies. Each folder contains a fully linked
three-statement financial model (Excel), a DCF and relative valuation, and a one-page investment
recommendation — built from scratch, not downloaded from a template.

| Company | Sector | Primary method | Fair value | Price (Aug-2026) | Verdict | Rating |
|---|---|---|---|---|---|---|
| [Tata Motors Passenger Vehicles (TMPV)](tata-motors/) | Autos (JLR + India PV) | DCF (mid-year) | ₹468 | ₹331 | Undervalued (+41%) | **BUY** |
| [Asian Paints](asian-paints/) | Decorative paints | Relative (48× FY27E EPS), DCF cross-check | ₹2,375 | ₹2,628 | Overvalued (−10%) | **HOLD** |

## The two calls, one line each

- **Tata Motors PV — BUY.** After the CV demerger, the market prices JLR's cyber-attack and tariff stress as permanent.
  At ~14× FY27E earnings vs 22–37× for pure-India auto peers, even the bear-case DCF (₹335) sits above today's price.
- **Asian Paints — HOLD.** A great company at a not-great price. Net cash, ROCE heading back to ~29%, volumes recovering —
  but at 58× trailing earnings with Birla Opus and JSW attacking pricing power, the stock is ~10% ahead of fair value. Buy below ~₹2,140.

## What's in each model

Twelve linked sheets, in the same order for every company:

`Cover → Historical Data → Ratio Analysis → Assumptions → Working Capital → Dep & Capex → Debt Schedule → Income Statement → Balance Sheet → Cash Flow → Valuation → Recommendation`

- **Driver-based, documented assumptions.** Every input has a one-line justification beside it
  (management guidance, peer data, or historical range). Asian Paints revenue is built as volume × price/mix;
  Tata Motors revenue is reconciled to JLR (£→₹) and India PV segment growth.
- **Integrity.** Balance sheet balances every year, cash flow ties to the balance-sheet cash movement, and a `Checks`
  sheet (Tata Motors) runs seven controls that must all read PASS.
- **Valuation.** WACC from CAPM (6.5% G-Sec, 6% ERP, company beta), 5-year FCFF DCF with terminal growth,
  WACC × g sensitivity grid, bear/base/bull scenarios, and a peer-multiple cross-check.
- **Colour convention.** Blue = hard-coded inputs, black = formulas, green = links to other sheets. Negatives in parentheses.
- **Data.** Historical financials from screener.in (consolidated), cross-checked against annual reports and
  investor presentations. Market data as of August 2026.

## Key assumptions at a glance

| | Tata Motors PV | Asian Paints |
|---|---|---|
| Revenue growth FY27E → FY31E | 12% → 5% | 13% → 9% |
| EBITDA margin FY27E → FY31E | 9.5% → 12.0% | 18.2% → 19.5% |
| Capex % of revenue | 9% → 7.5% | 5% → 4% |
| Beta | 1.15 | 0.85 |
| WACC | 10.0% | 11.5% |
| Terminal growth | 3.0% | 4.5% |
| Terminal value % of EV | 81% | 76% |

## Track record

Forecasts will be compared with reported results every quarter and logged in each company folder,
starting with Q2 FY27 results (Oct–Nov 2026). The point is to learn where the model was wrong and why.

## Disclaimer

Personal research for learning and portfolio purposes only. Not investment advice. All figures in ₹ crore
unless stated; prices as of August 2026.

---
