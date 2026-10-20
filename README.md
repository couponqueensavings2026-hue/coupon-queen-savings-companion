# Coupon Queen Savings Companion

A luxury-styled savings planner for budgeting, deal tracking, shopping checklists, and savings goals.

## Features
- Dashboard with budget, savings, spending, deals, and remaining checklist items
- Budget planner with remaining-balance tracking
- Coupon and deal tracker with validation, edit, and delete actions
- Shopping checklist with complete and incomplete sections
- Savings goals with progress bars and remaining amount tracking
- Local browser storage with backup import/export and CSV export
- Offline support through a service worker and installable manifest
- Static site ready for GitHub Pages hosting

## GitHub Pages setup
This repository is configured to deploy from the `main` branch using GitHub Actions.

After pushing changes to GitHub:
1. Open the repository in GitHub.
2. Go to Settings → Pages.
3. Under Build and deployment, choose Source: GitHub Actions.
4. Wait for the workflow to run and publish the site.

Expected URL:
https://couponqueensavings2026-hue.github.io/coupon-queen-savings-companion/

## Data note
Your browser data is stored locally and can be lost if site data is cleared or if you switch devices.

## Backup and import
- Download JSON backup from the app to save a complete copy of your data.
- Import a JSON backup to restore prior data.
- Export a CSV file for quick spreadsheet sharing.
