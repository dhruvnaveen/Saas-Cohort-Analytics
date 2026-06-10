# Cohort Analytics

Client-side SaaS cohort analytics: upload a subscription CSV, get a retention
heatmap, NRR waterfall, churn reason breakdown, and a grounded AI insight summary.

- 100% client-side — uploaded data never leaves the browser.
- Auto-detects columns from any export (Stripe, Chargebee, spreadsheets, EU
  formats); interactive mapping panel with sample previews for anything ambiguous.
- Handles messy real-world data: currency strings, Excel serial dates,
  day/month vs month/day inference, junk rows.
- AI summary uses a two-stage grounded pipeline — findings are computed
  deterministically in code, the model only phrases them, and a post-hoc
  verifier checks every number in the output against the computed facts.


