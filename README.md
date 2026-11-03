# 💼 Freelance True Hourly & Day Rate Calculator 💼

> Interactive client-side freelance rate and 1099 vs. W-2 salary equivalence calculator. Computes billable hourly, full-day, half-day, and retainer rates with zero external dependencies.

A fast, zero-dependency business finance utility built for freelancers, independent consultants, agencies, and 1099 contractors to convert a target annual take-home or W-2 salary into accurate client billing rates.

---

## Features

- **1099 vs. W-2 Equivalence Modeling:** Compares your required 1099 billable rate directly against an equivalent 2,080-hour W-2 hourly wage.
- **Realistic Billable Utilization:** Factors in unpaid PTO, holidays, sick days, and the weekly split between billable client hours and non-billable admin/sales time.
- **Taxes, Health Insurance & Retirement:** Accounts for self-employment + income taxes, self-paid health/dental/vision premiums, and lost employer 401(k) match.
- **Dynamic Business Overhead Tracker:** Add custom monthly or annual deductible expenses or select from common presets (SaaS subscriptions, CPA/bookkeeping, E&O insurance, hardware refresh, co-working).
- **Complete Client Rate Tiers:** Outputs True Hourly Rate, Break-Even Hourly Floor, Full-Day Rate (8h), Half-Day Rate (4h), Weekly Retainer, and Monthly Retainer.
- **One-Click Rate Sheet Export:** Copy a formatted client rate card and financial summary directly to your clipboard.
- **SEO & Search Rich Snippets:** Built-in Schema.org `WebApplication` and `FAQPage` JSON-LD structured data.
- **Compliance & Privacy:** Includes Privacy Policy, Terms & Financial Disclaimer, Advertising Disclosure modals, and `ads.txt`.

---

## Technology Stack

- **HTML5 & CSS3:** Responsive modern dark theme, CSS Grid & Flexbox, mobile-friendly touch targets (`>= 44px`).
- **Vanilla JavaScript:** 100% in-browser, defensive client-side execution with zero external frameworks, npm packages, or CDN dependencies.

---

## Local Development & Usage

No build steps or installation required. Open `index.html` directly in any browser:

```bash
# Clone the repository
git clone https://github.com/setay-labs/freelance-hourly-rate-calculator.git

# Open directly in browser
open index.html # macOS
start index.html # Windows
```

---

## License

This project is open-source and available under the [MIT License](LICENSE).
