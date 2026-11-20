# Pharmacy Near Me

Find a pharmacy near you — hours, services and savings. A static single-page site built for GitHub Pages.

**Live site:** https://pharmacynearby.github.io

## What it is

An original, English-language (US) pharmacy information site: 5 tools, an over-the-counter reference table, 6 guides, FAQ, About and Disclaimer. Pure HTML5, CSS3 and vanilla JavaScript — no frameworks, no build step, no backend. All tools run locally in the browser.

## Tools (all client-side)

1. **Prescription Refill Schedule Tracker** — refill date, days left and order-by date from last fill date and days of supply.
2. **Medicine Expiry Checker** — days remaining until the expiry date, with expired / expiring-soon status.
3. **Generic vs Brand Price Comparison** — monthly, yearly and total savings, and percentage cheaper.
4. **Daily Pill Schedule Planner** — doses spread evenly across waking hours from a wake-up time.
5. **Pharmacy Services Checklist** — 8 services to ask about, with coverage percentage.

Also included: a reference table of common over-the-counter medicine categories and typical uses, six practical guides, FAQ, About and Disclaimer.

## Disclaimer

Informational only — not medical advice. Always consult your pharmacist or doctor about medicines, doses, interactions and symptoms.

## Deploy to GitHub Pages

1. Create a public repository named **pharmacynearby** under the GitHub organization **pharmacynearby**.
2. Upload all files from this folder to the repository root.
3. In the repository: **Settings → Pages → Build and deployment → Deploy from a branch → branch `main`, folder `/ (root)` → Save.**
4. The site goes live at **https://pharmacynearby.github.io** within a few minutes.

## Local preview

```bash
python3 -m http.server 8000
# open http://localhost:8000/
```
