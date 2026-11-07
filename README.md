# amazon-fba-calculator-tool
Amazon FBA Reverse Sourcing Cost &amp; Margin Calculator
# Amazon FBA Dimensional Margin Calculator

![HTML5](https://img.shields.io/badge/HTML5-E34F26?logo=html5&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?logo=javascript&logoColor=black)
![No Dependencies](https://img.shields.io/badge/dependencies-none-brightgreen)
![License: MIT](https://img.shields.io/badge/license-MIT-blue)

A **single-file, zero-dependency** web calculator for estimating Amazon FBA unit economics on the US marketplace. It combines package dimensions, dimensional (volumetric) weight, size-tier classification, weight-tier fulfillment fees, referral fees, monthly storage, and optional 2026 surcharges to produce a real-time net profit, net margin, and break-even price.

> **Not affiliated with Amazon.** All rates are simplified approximations for planning and educational purposes. Always verify against Seller Central before pricing decisions.

---

## Features

- **Real-time calculation** — every input change instantly updates profit, margin, and fee breakdown.
- **Dimensional weight aware** — billable weight is `max(actual weight, volumetric weight)`, using the Amazon divisor of `139 in³/lb` (equivalent to `cm³ / 5000`).
- **Automatic size-tier detection** — Small Standard / Large Standard / Oversize based on sorted package dimensions and billable weight.
- **Weight-tier fulfillment fees** — Large Standard and Oversize fees change with every weight bracket, so 1 lb, 5 lb, and 15 lb produce different results.
- **Optional 2026 surcharges** — fuel & logistics surcharge, inbound placement fee, low-inventory-level fee, and aged-inventory surcharge can be toggled independently.
- **Break-even snapshot** — solves the sale price at which net profit equals zero.
- **Imperial / Metric toggle** — inches & pounds or centimeters & kilograms, converted internally.
- **No build step, no framework, no CDN** — one `index.html` file, open it in any modern browser.

---

## Quick Start

### Online demo

If GitHub Pages is enabled for this repository:
