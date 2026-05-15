# Amazon Tech Trends Sales Insight 2026

Created by Hieu Nguyen

Professional dashboard and analysis report for the Amazon Big Sales Dataset 2026. The project is designed as a clean static website, so it can be opened locally or published directly with GitHub Pages.

## Project Files

| File | Purpose |
|---|---|
| `index.html` | Interactive dashboard with KPI cards, category charts, scatter plot, search, filters, and leaderboard |
| `Amazon_Big_Sales_Analysis_2026.ipynb` | Python notebook with data clean up, validation, full analysis, visualizations, and recommendations |
| `REPORT.md` | Professional analysis report with executive summary, insights, and recommendations |
| `Amazon_Big_Sales_Dataset_2026.csv` | Source dataset |
| `Amazon_Big_Sales_Dataset_2026_Cleaned.csv` | Cleaned and feature-enriched dataset exported from the notebook |
| `requirements.txt` | Python packages needed for the notebook |

## Dashboard Features

- Executive KPI summary
- Category performance comparison
- Review-share donut chart
- Price versus rating bubble chart
- Product leaderboard with search, sort, and category filters
- Sales-potential proxy using `Price_USD x Review_Count`

## How To View

Open `index.html` in a browser. No install step is required.

## Run The Notebook

Use the local virtual environment:

```powershell
.\.amazonvenv\Scripts\python.exe -m pip install -r requirements.txt
```

Then open `Amazon_Big_Sales_Analysis_2026.ipynb` and select `.amazonvenv` as the notebook kernel.

## GitHub Pages

1. Push this repository to GitHub.
2. Go to repository **Settings**.
3. Open **Pages**.
4. Set the source to the main branch and root folder.
5. Save, then open the GitHub Pages URL after deployment finishes.

## Important Methodology Note

The dataset does not include actual units sold or realized revenue. For that reason, the dashboard and report use **sales potential** as a transparent directional proxy:

```text
Sales Potential = Price_USD x Review_Count
```
