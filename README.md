# Zambia Soya Beans Export Pulse (2021–2022)

This repository supports the analysis and insights from the *Zambia’s Soya Beans Export Pulse* report, covering export volumes, destination markets, price trends, and local versus export value dynamics.

The analysis uses a combination of:
- **Excel** for production and competitor data,
- **Tableau** for export volume trends,
- **Python** for export price analysis,
- **Excel/Table views** for local vs export price comparisons.

The goal is to present a structured, data-driven perspective on Zambia’s soya bean export performance over the 2021–2022 period and contextualize it within local market conditions.

---

## Repository Structure

---

## Project Overview

Zambia’s soya bean export performance showed mixed trends between 2021 and 2022:

- **Export destination patterns (2021)** show South Africa, India, and Tanzania as the leading partners in value and quantity terms. 0
- **Export destination patterns (2022)** reveal a shift in partner rankings, though South Africa and Tanzania remain significant buyers. 1
- Total export value declined from roughly **USD 21.5 million in 2021** to about **USD 12.3 million in 2022**, with similarly lower quantities exported. 2

The repository’s datasets and analyses aim to replicate and extend these insights, allowing interactive exploration of:
- year-on-year export volume changes,
- structure of export destination markets,
- price evolution over the period,
- comparison of local market prices against export price performance.

---

## Methods & Tools

### Data Preparation
- Raw agricultural and trade data were cleaned and formatted in **Excel**.
- Time series and comparative tables were prepared to support trend analysis.

### Export Trend Visualization
- **Tableau** was used to create export volume trend visuals by year and partner country.
- Visuals include bar charts, line trends, and country comparisons.

### Price Analytics
- **Python** (Pandas, Matplotlib/Seaborn) was used to:
  - load and clean export price data,
  - generate price trend charts,
  - calculate basic descriptive statistics.

### Competitor & Price Comparisons
- Additional price and competitor data were analysed in **Excel**,
  with comparisons between local market prices and typical export rates.

---

## Key Insights (To be updated)

Once all visuals and tables are added, this section will summarize key insights such as:

- Year-to-year percentage change in export value and quantity.
- Top export market destinations and shifts between 2021 & 2022.
- Export price trends and comparison with local price dynamics.
- Observations from competitor pricing analysis.

These findings will be supported with narrative text, charts, and dashboard links.

---

## How to Use

1. Clone this repository.
2. Open the `data/` folder to explore raw and cleaned datasets.
3. View visualizations in `analysis/` or `dashboards/`.
4. Run the Python notebook in a Jupyter environment (`price_analysis.ipynb`).
5. Update visual assets as available (Tableau/Excel dashboards).

---

## Notes & References

The export figures in this project draw on international trade statistics for Zambia:
- Zambia exported ~USD 21.5 million of soya beans in 2021. 3
- Export value dropped to approximately USD 12.3 million in 2022. 4

Additional data sources and contextual notes can be added once production and local pricing datasets are included.

---

## License

This repository is released under the MIT License (or choose your preferred open license).

---
