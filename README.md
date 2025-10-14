
# Money Tracker

A lightweight, single-page app to track earnings and spendings with charts and local persistence.

## Features
- Add income/expense with date, category, and note
- Filters: type, category, date range, search
- Pagination for transaction list
- LocalStorage persistence
- Export/Import JSON
- Sample data seeding
- Charts (Chart.js): Monthly Income vs Expense, Expense by Category

## Quick Start
1. Click "Seed Sample" to see a demo data (optional).
2. Add your transactions using the form.
3. Click on the Currency ISO next to Export JSON to change the currency.
4. Filter and browse the list; use Prev/Next for pagination.
5. Export data to JSON to back up; Import JSON to restore.

## Data & Privacy
- All data is stored locally in your browser via LocalStorage under key `money-tracker:v1`.
- Use "Reset" to clear all data.

## Tech Stack
- TailwindCSS via CDN
- Chart.js via CDN
- Vanilla JS, no build step required
