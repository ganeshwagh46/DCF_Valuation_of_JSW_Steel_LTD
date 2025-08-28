# DCF_Valuation_of_JSW_Steel_LTD

## File: DCF Valuation Of JSW Steel LTD.xlsx

Purpose This workbook implements a Discounted Cash Flow (DCF) valuation for JSW Steel Ltd. It collects historical financials, calculates free cash flows, and discounts projected cash flows to estimate enterprise value (EV) and equity value per share.

## Quick start — where to look

Open the DCF sheet — this contains the core valuation (projections, discounting, terminal value, valuation summary).

Historical FS — historical income statement / balance sheet data used to derive growth, margins and working capital trends.

Cash Flow / Cash Flow Data — cash flow statements and underlying cash flow items.

Raw Balance Sheet — raw balance-sheet items and reconciliations.

Ratio Analysis — computed financial ratios (margins, ROE, leverage) used as sanity checks.

Beta and Rm — inputs / calculations for cost of equity (beta, market return) used in WACC.

Data Sheet / Data> — intermediate data tables and normalized inputs. Update this if you are refreshing raw inputs.

If you want the valuation results quickly, check the top-right of the DCF sheet for the Summary / Valuation block (EV, Net Debt, Equity Value, Per-Share Value).

## Recommended workflow to update the model

Update historicals — paste the latest audited / quarterly numbers into Historical FS, Raw Balance Sheet and Cash Flow Data.

Refresh inputs — verify Beta, Rm and any other market inputs. Check Data Sheet / Data> for cleaned series.

Adjust projections — in the DCF sheet change revenue growth rates, margin assumptions or capital expenditure / working capital drivers.

Recompute WACC — ensure cost of equity (from Beta & Rm) and cost of debt / tax rate are correct.

Check outputs — review the Valuation Summary in DCF and compare against Ratio Analysis for reasonableness.

## What to edit (inputs) vs. what not to edit (calculations)

Edit: cells clearly labeled as Input, Assumption or in sheets named Data Sheet, Beta, Rm and Historical FS (when updating raw numbers).

Do not edit: formula cells in the DCF sheet that calculate FCF, discount factors, terminal value and final valuations unless you are intentionally changing the model logic.

## Key calculations (how valuation is built)

Normalize historical financials using Historical FS and Raw Balance Sheet.

Project income statement items (Revenue → EBITDA → EBIT) and derive Free Cash Flow (FCF) using the Cash Flow sheets (operating cash flow, capex, change in working capital).

Compute WACC using Beta (sheet Beta), market return (Rm), cost of debt and target capital structure.

Discount projected FCFs and add Terminal Value (Gordon Growth or exit multiple) to obtain Enterprise Value (EV).

Subtract Net Debt / Adjustments to get Equity Value and divide by shares outstanding for Value per Share.

## Sensitivity analysis & scenario testing

This workbook does not appear to contain a dedicated sensitivity / scenario table. Recommended options:

Add a Sensitivity sheet and use two-way data tables to show valuation sensitivity to WACC and terminal growth / margin assumptions.

Create scenario tabs (e.g., Base, Upside, Downside) that copy the DCF sheet inputs and change assumptions.

## Assumptions to verify before sharing

Forecast horizon (number of projection years) and terminal growth.

Revenue growth drivers and whether they are explicit (by segment) or blended.

Capex / Depreciation policy and how deeply it links to fixed asset schedules.

Working capital dynamics (days receivable, payable, inventory).

Tax rate used for NOPAT / WACC.

Shares outstanding used to compute per-share value.
