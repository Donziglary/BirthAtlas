```markdown
# 🌍 BirthAtlas: Mapping Birth Probability and the Problem of Moral Luck

[![Python](https://img.shields.io/badge/Python-3.8%2B-blue.svg)](https://www.python.org)
[![Pandas](https://img.shields.io/badge/Pandas-Data%20Analysis-orange.svg)](https://pandas.pydata.org)
[![Plotly](https://img.shields.io/badge/Plotly-Interactive%20Maps-brightgreen.svg)](https://plotly.com)
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)

**BirthAtlas** is an interdisciplinary, data-driven exploration into one of the most compelling concepts in moral philosophy: **Moral Luck**, specifically manifested as **Birth Luck** (the "birth lottery"). Utilizing official World Bank demographic datasets spanning from **1993 to 2020**, this project models, analyzes, and visualizes the statistical probability of an individual being born into any given nation across the globe.

> 🧠 **Philosophical Underpinning:** *Moral luck* occurs when an agent is subjected to moral or qualitative evaluation despite the fact that crucial aspects of their situation depend on factors entirely beyond their control. We do not choose our country of birth; yet, this arbitrary geographical lottery heavily dictates our life expectancy, systemic opportunities, economic mobility, and fundamental freedoms.

---

## ✨ Key Features
- **Macro-Level Data Processing:** Ingests, cleans, and aggregates global population totals and crude birth rates for all recognized nations over a 27-year timeline.
- **Birth Probability Modeling:** Implements a mathematical framework to isolate and compute a country’s exact share of global births per annum as a standardized metric.
- **Dynamic Choropleth Mapping:** Leverages **Plotly Express** to construct animated, highly interactive global maps with integrated timeline sliders to showcase longitudinal shifts.
- **End-User Deployment:** Compiles visualizations into a standalone, lightweight `index.html` file, designed for seamless public showcase, portfolios, or web integration.

---

## 📂 Repository Structure
The project follows clean, industry-standard directory conventions optimized for production data science workflows:

```text
BirthAtlas/
│
├── data/
│   ├── raw/
│   │   ├── pop_total.csv         # Raw World Bank total population data
│   │   └── birth_rates.csv       # Raw World Bank crude birth rate data (per 1,000 people)
│   └── processed/
│       └── birth_probability.csv # Computed final dataset containing the birth probability index
│
├── notebooks/
│   ├── 01_process_data.ipynb     # Pipeline for data cleaning, missing value handling, and merging
│   └── 02_visualize.ipynb        # Engineering interactive Plotly choropleth maps
│
├── index.html                    # Decoupled, production-ready interactive map for end-users
├── .gitignore                    # Standard exclusions (virtual environments, cache, system files)
├── requirements.txt              # Explicit library dependencies and version pinnings
└── README.md                     # Project documentation (this file)