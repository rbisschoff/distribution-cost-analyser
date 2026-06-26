# Distribution Cost Analyser

A single-file HTML tool for hospitality operators — hotels, serviced apartments, STR — to compare **true** distribution costs across Direct and OTAs, not just headline commission.

Part of the **Operator Series** by [Roger Bisschoff](https://linkedin.com/in/roger-bisschoff) (15 years in European hospitality distribution).

## What it does

- Compare any OTA mix (Booking.com, Expedia, Airbnb, or your own) against Direct in one view
- Include hidden costs: promo programs, payment processing, support time, website & marketing
- See which channel is actually cheapest, in % and in currency
- Run **opportunity simulations**: OTA share decrease, OTA-to-OTA moves, and extra marketing spend
- Live re-run when results are open, presets, currency selector, annual/monthly input toggle

## Try it

**On your computer:** open `index.html` in any browser. No install, no build step.

**Live demo (GitHub Pages):**

```
https://YOUR-GITHUB-USERNAME.github.io/distribution-cost-analyser/
```

Upload `index.html` and `og-image.svg` to the repo root for social previews and Pages hosting.

## Publish on GitHub Pages

1. Create a GitHub repo (e.g. `distribution-cost-analyser`)
2. Upload `index.html` and `og-image.svg`
3. Go to **Settings → Pages** → deploy from the `main` branch → Save
4. Your live URL will be active in a minute or two

## Share & export

- **Share** — copies a URL with inputs encoded in the hash (`#s=...`)
- **Copy summary** — plain-text executive summary for email or Slack
- **Print** — save as PDF with a print header (inputs hidden)

## Technical notes

- Single self-contained HTML file (inline CSS + JavaScript) plus `og-image.svg` for link previews
- Chart.js 3.9.1 via CDN
- Inputs auto-save to `localStorage` (`dca-state`; migrates from legacy `dca-v17-state`)
- Customer service cost scales from revenue ÷ average booking value
- All calculations run on annual figures; monthly mode only affects how you enter revenue and flat costs

## Licence

Built for operator use and portfolio. Add a licence if you publish publicly.
