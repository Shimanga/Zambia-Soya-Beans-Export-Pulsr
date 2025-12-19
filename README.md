# Zambia Soya Beans Export Pulse (2021–2022)

This repository supports the analysis and insights from the *Zambia’s Soya Beans Export Pulse* report, covering export volumes, destination markets, price trends, and local versus export value dynamics.

The analysis uses a combination of:
- **Excel** for production and competitor data,
- **Tableau** for export volume trends,
- **Python** for export price analysis,
- **Excel/Table views** for local vs export price comparisons.

The goal is to present a structured, data-driven perspective on Zambia’s soya bean export performance over the 2021–2022 period and contextualize it within local market conditions. The core question driving this analysis is: **Does exporting soya beans offer better returns for Zambian farmers and agribusinesses than selling locally?**

**Original Article:** [Zambia’s Soya Beans Export Pulse (2021–2022 Data)](https://agricultureinzambia.com/zambias-soya-beans-export-pulse-2021-2022-data/)

---

## Repository Structure

---

## Project Overview

Zambia’s soya bean export performance showed mixed trends between 2021 and 2022:

- **Export destination patterns (2021)** show South Africa, India, and Tanzania as the leading partners in value and quantity terms.
- **Export destination patterns (2022)** reveal a shift in partner rankings, though South Africa and Tanzania remain significant buyers. 
- Total export value declined from roughly **USD 21.5 million in 2021** to about **USD 12.3 million in 2022**, with similarly lower quantities exported. 

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

![Export Trend analysis](images/Export_data.png)

### Price Analytics
- **Python** (Pandas, Matplotlib/Seaborn) was used to:
  - load and clean export price data,
  - generate price trend charts,
  - calculate basic descriptive statistics.

![Local price analysis](images/Local_price_analysis_per_kg.png)

### Competitor & Price Comparisons
- Additional price and competitor data were analysed in **Excel**,
  with comparisons between local market prices and typical export rates.

![Competitor price analysis](images/Competitor_analysis.png)
---

## Key Insights
- **Production Concentration**: Central and Eastern Provinces dominate Zambia's soya bean output.
- **Export Price Premium**: Converted export prices to Angola, DRC, India, and South Africa consistently exceeded the local FRA price.
- **Volume-Price Trade-off**: Markets like India paid higher prices for smaller volumes, while Tanzania and Zimbabwe took larger volumes at lower rates.
- **Competitive Positioning**: Zambia occupies a middle-ground, exporting at higher prices than Mozambique but competitively with Tanzania and South Africa.
- **Feasibility Hinges on Scale**: The export price advantage can be eroded by logistics costs, making organization and aggregation critical for profitability.
---

## How to Use

1. Clone this repository.
2. Open the `data/` folder to explore raw and cleaned datasets.
3. View visualizations in `analysis/` or `dashboards/`.
4. Run the Python notebook in a Jupyter environment (`soya_beans_local_price_analysis.py`).
5. Update visual assets as available (Tableau/Excel dashboards).

---

## Notes & References

The export figures in this project draw on international trade statistics for Zambia:
- Zambia exported ~USD 21.5 million of soya beans in 2021.
- Export value dropped to approximately USD 12.3 million in 2022.

Additional data sources and contextual notes can be added once production and local pricing datasets are included.
As cited in the original article:
*   **Export Data**: FAO (Food and Agriculture Organization)
*   **Regional Export Data**: World Bank
*   **Production Data**: Zamstats (Zambia Statistics Agency)
*   **Local Price Data**: PMRC Zambia & Parliament of Zambia
---

## Conclusion
This analysis demonstrates that exporting soya beans can be economically attractive, offering a price premium over local FRA prices. However, success is not automatic—it depends heavily on achieving scale, controlling logistics costs, and targeting the right destination markets. This repository provides the data and code backbone to support these insights.

---
*Analysis and article by Shimanga Mubitana.*
```
