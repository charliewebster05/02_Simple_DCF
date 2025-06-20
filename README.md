A simple, flexible Python model for calculating the **intrinsic value per share** of a company using the **Discounted Cash Flow (DCF)** method. Built to help automate valuation workflows based on projected Free Cash Flows, WACC, terminal growth, and capital structure.

---

## Features

- Calculate intrinsic value per share from future FCF projections
- Supports custom WACC and terminal growth rates
- Includes terminal value calculation
- Adjusts for net debt and shares outstanding
- Optional: plot intrinsic value vs market price
- Clean syntax with basic error handling

---

## How It Works

The model:
1. Discounts projected free cash flows using WACC
2. Estimates terminal value based on perpetual growth
3. Subtracts net debt
4. Divides by shares outstanding to get **intrinsic value per share**

