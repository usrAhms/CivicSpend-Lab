# CivicSpend Lab — Invoice Review Workspace

A browser-based prototype for exploring procurement invoice review workflows using **synthetic data**.

## Live demo

After enabling GitHub Pages, your link will be `https://YOUR-GITHUB-USERNAME.github.io/civicspend-lab/`.

## Features

- Import a local CSV (columns: `id,agency,vendor,date,amount`)
- Search and filter invoices and summarize spending
- Flag invoices with simple illustrative rules (possible duplicates, large amounts)
- Open invoice details and record review status, reviewer, and notes
- Persist review notes in browser localStorage
- Export filtered invoices or review outcomes as CSV
- Restore synthetic sample data

## Getting started

Open `index.html` directly or enable GitHub Pages for this repository (`main` branch, root). The page requires no dependencies or backend.

## Sample CSV

```csv
id,agency,vendor,date,amount
INV-001,Agency North,Example Vendor,2026-01-12,42000
INV-002,Agency West,Another Vendor,2026-02-15,97000
```

## Limitations and disclosure

This is an AI-assisted educational prototype. All included invoices are fictional. Risk flags are **rule-based demonstrations**, not machine-learning forecasts, legal compliance conclusions, or evidence of fraud. Imported CSV data is processed locally in your browser, not uploaded to a server. Browser-local notes may be deleted by clearing site data. Do not upload actual sensitive procurement data.
