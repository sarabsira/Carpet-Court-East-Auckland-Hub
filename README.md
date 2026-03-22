# East Auckland Hub — FY27 Budget Tracker

Live budget tracking dashboard for Carpet Court East Auckland Hub (Newmarket, Botany, Mt Wellington).

## Features

- **4 views** — Cluster total + each individual branch
- **Monthly actuals entry** — Log sales, GP, EBITDA, flooring & CS splits
- **Live trajectory** — Running projection against budget based on recent actuals
- **Charts** — Monthly budget vs actual bars, cumulative YTD line, GP% trend, EBITDA, full-year outlook
- **Monthly detail table** — Variance $ and % by month, click any row to edit
- **CSV export** — Download full year data per branch
- **Persists in browser** — Data stored in localStorage (no backend needed)

## Deploy to Cloudflare Pages

1. Push this repo to GitHub
2. Go to Cloudflare Pages → Create application → Connect to Git
3. Select your repo
4. Build settings:
   - Framework preset: None
   - Build command: (leave blank)
   - Build output directory: /
5. Click Save and Deploy

Your dashboard will be live at https://your-project.pages.dev

## Sharing

Once deployed, share the Cloudflare URL. Note: each user's actuals data is stored in their own browser localStorage — data does not sync across users automatically. Export CSV to consolidate if needed.

## Updating Budget Figures

Budget figures are inside index.html in the BUDGETS constant near the top of the script block. Edit sales, gp, or ebitda for any store and redeploy.

## FY27 Budget Reference

| Branch         | FY27 Sales | FY27 GP | FY27 EBITDA |
|----------------|------------|---------|-------------|
| Cluster Total  | $12.00m    | $3.29m  | $1.09m      |
| Newmarket      | $3.43m     | $943k   | $298k       |
| Botany         | $3.17m     | $845k   | $164k       |
| Mt Wellington  | $5.40m     | $1.50m  | $624k       |
