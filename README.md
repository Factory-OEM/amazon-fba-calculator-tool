# Amazon FBA Dimensional Margin Calculator

[![Live Demo](https://img.shields.io/badge/Live%20Demo-factory--oem.com-4f46e5)](https://factory-oem.com/Ai/Amazon-FBA-Calculator/)
![Status](https://img.shields.io/badge/status-online-brightgreen)
![Platform](https://img.shields.io/badge/platform-web%20browser-blue)
![Cost](https://img.shields.io/badge/price-free-brightgreen)

A free online calculator for estimating **Amazon FBA unit economics** on the US marketplace. Enter your sale price, product cost, package dimensions, and shipping weight — the tool instantly returns net profit, net margin, fee breakdown, and break-even price.

It accounts for **dimensional (volumetric) weight**, **automatic size-tier classification**, **weight-tier fulfillment fees**, referral fees, monthly storage, and optional 2026 surcharges.

**🔗 Open the calculator: [https://factory-oem.com/Ai/Amazon-FBA-Calculator/](https://factory-oem.com/Ai/Amazon-FBA-Calculator/)**

> **Not affiliated with Amazon.** All rates are simplified approximations for planning and educational purposes. Always verify against Seller Central before pricing decisions.

---

## How to Use

1. Open **[https://factory-oem.com/Ai/Amazon-FBA-Calculator/](https://factory-oem.com/Ai/Amazon-FBA-Calculator/)** in any modern browser.
2. Enter your **sale price**, **target margin**, and **product cost (COGS)**.
3. Choose a **referral fee category** (8% / 15% / 17%).
4. Enter **package dimensions** and **shipping weight** — switch between Imperial (in/lb) and Metric (cm/kg) at any time.
5. Toggle optional surcharges if they apply to your scenario.
6. Read the results panel on the right: net profit, net margin, fee breakdown, and break-even price.

No account, sign-up, or installation is required. The tool runs entirely in your browser.

---

## Features

- **Real-time calculation** — every input change instantly updates profit, margin, and fee breakdown.
- **Dimensional weight aware** — billable weight is the greater of actual weight and volumetric weight, using the standard Amazon divisor (`139 in³/lb`, equivalent to `cm³ / 5000`).
- **Automatic size-tier detection** — classifies each package as Small Standard, Large Standard, or Oversize based on sorted dimensions and billable weight.
- **Weight-tier fulfillment fees** — Large Standard and Oversize fees change with every weight bracket, so 1 lb, 5 lb, and 15 lb produce different results.
- **Optional 2026 surcharges** — fuel & logistics surcharge, inbound placement fee, low-inventory-level fee, and aged-inventory surcharge can be toggled independently.
- **Break-even snapshot** — solves the sale price at which net profit equals zero.
- **Imperial / Metric toggle** — enter values in inches & pounds or centimeters & kilograms; conversion is automatic.
- **No installation** — works in any modern desktop or mobile browser.

---

## How It Calculates

### 1. Billable (shipping) weight
