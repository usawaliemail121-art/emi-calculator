# EMI Calculator

A free, fast, and private **EMI calculator** for Indian home, car, and personal loans — deployed on GitHub Pages.

**Live site:** https://usawaliemail121-art.github.io/emi-calculator/

## Features

- **Instant EMI calculation** — loan amount, interest rate, and tenure (years + months) inputs with synced sliders and number fields.
- **Full results** — monthly EMI, total interest payable, total payment (principal + interest).
- **Payment breakdown** — SVG donut chart and stacked bar showing principal vs. interest share.
- **Amortization schedule** — year-by-year and month-by-month repayment table with running balance and totals.
- **Loan presets** — Home Loan, Car Loan, and Personal Loan quick presets with typical Indian rates.
- **Indian conventions** — ₹ formatting via `en-IN` locale, plus lakh/crore labels alongside numerals.
- **Educational content** — the EMI formula explained with a worked example, a "How to use" guide, and an in-depth FAQ.
- **SEO ready** — meta description, keywords, Open Graph/Twitter tags, canonical URL, and JSON-LD structured data (WebApplication + FAQPage).
- **AdSense ready** — clearly marked placeholder slots (below hero, mid-content, before footer); paste ad unit code after approval.
- **Zero dependencies** — clean vanilla HTML/CSS/JS in a single page; all math runs client-side, nothing is uploaded.

## Pages

| File | Purpose |
|---|---|
| `index.html` | The EMI calculator + formula, how-to, and FAQ content |
| `about.html` | About the site |
| `privacy-policy.html` | Privacy policy (incl. Google AdSense / third-party cookie disclosures) |
| `robots.txt` | Crawler rules |
| `sitemap.xml` | Sitemap for search engines |

## How the calculation works

The calculator uses the standard reducing-balance formula used by Indian banks and NBFCs:

```
EMI = P × r × (1 + r)^n / ((1 + r)^n − 1)
```

where `P` is the principal, `r` the monthly interest rate (annual ÷ 12 ÷ 100), and `n` the tenure in months. The amortization schedule simulates each monthly instalment, splitting it between interest (on the outstanding balance) and principal.

## Deployment (GitHub Pages)

1. Files live on the `main` branch (site root).
2. GitHub Pages is enabled with source branch `main`, path `/ (root)`.

## License

This project is provided as-is for personal and educational use. No warranty — verify all loan figures with your lender.
