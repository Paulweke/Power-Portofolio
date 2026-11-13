# Dashboards

Interactive HTML versions of two Power BI reports, hosted free on GitHub Pages.

- `index.html` – landing page
- `pharmaca.html` – Pharmaca Executive Dashboard
- `insurance.html` – Insurance Risk Analysis (6 pages)

Each page is a single self-contained file (data embedded; only Chart.js is loaded from cdnjs).

## Publish
1. Create a repo and upload these files to the root.
2. Settings > Pages > Branch: `main`, folder `/ (root)` > Save.
3. Open `https://<username>.github.io/<repo>/`.

## Notes
- Insurance: customer names removed; IDs shown instead.
- Data is aggregated client-side; filters mirror the original Power BI slicers.
