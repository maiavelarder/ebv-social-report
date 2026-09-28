# EBV Social Media Report

Live dashboard: https://maiavelarder.github.io/ebv-social-report/

Data lives in data.csv (or a Google Sheet linked in config.js). Default password: ebv2026. Change it with make-password.html.

## Every month (10 min)

1. Meta Business Suite > Insights > switch to **Instagram**.
2. **Results** tab, set the date range to last month: note Views (Instagram), Reach, Content interactions, Link clicks, Visits.
3. **Audience > Trends**, same dates: note Follows and Unfollows.
4. **Audience > Demographics**: note total Followers and the Top countries % (the only chance to capture that month's country split).
5. Add one row to the data. followers = the Demographics total. estimated = no.

## Good to know

* The password stops casual visitors. It is not bank-level security. The data is technically public to anyone who finds the repository.
* The page is hidden from Google search (noindex).
* To add Facebook or TikTok later, add rows with that platform name. The Platform filter picks them up automatically.
