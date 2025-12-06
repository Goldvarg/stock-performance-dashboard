# Stock Performance Dashboard

A simple dashboard that shows you which stocks are killing it and which ones are tanking - across different time periods from 1 day to 5 years.

## **[View Live Dashboard](https://goldvarg.github.io/stock-performance-dashboard/)**


<img width="1358" height="716" alt="Screenshot 2025-12-06 at 13 08 38" src="https://github.com/user-attachments/assets/ee0c02b9-f934-4c1f-9bc5-206feccfee04" />


## What it does

- Tracks **100 major stocks** (S&P 500 companies like Apple, Tesla, NVIDIA, etc.)
- Shows the **top 3 gainers** and **top 3 losers** for each time period
- Displays current price, percentage change, and a mini price chart
- Data refreshes every time you load the page

## Time periods

- 1 Day
- 1 Week
- 1 Month
- 1 Year
- 3 Years
- 5 Years

## Tech

- Pure HTML/CSS/JS (no frameworks)
- Chart.js for the sparkline charts
- Yahoo Finance data via CORS proxy
- Hosted on GitHub Pages

## Run locally

Just open `index.html` in your browser, or:

```bash
npx serve
```
