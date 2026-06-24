# 🌍 BirthAtlas: Mapping Birth Probability and Moral Luck

[![Python](https://img.shields.io/badge/Python-3.8%2B-blue.svg)](https://www.python.org)
[![Pandas](https://img.shields.io/badge/Pandas-Data%20Analysis-orange.svg)](https://pandas.pydata.org)
[![Plotly](https://img.shields.io/badge/Plotly-Interactive%20Maps-brightgreen.svg)](https://plotly.com)

---

## 🌐 LIVE DEMO: Interactive Map
Don't want to read the code? You can view the final interactive map directly in your browser:

### **[👉 CLICK HERE TO EXPLORE THE BIRTH ATLAS MAP 👈](https://donziglary.github.io/BirthAtlas/)**

---

## 🧠 The Concept: Moral Luck & The "Birth Lottery"
**BirthAtlas** is a data-driven exploration of **Moral Luck**. We do not choose our country of birth, yet this arbitrary "geographical lottery" heavily dictates our life expectancy, economic mobility, and fundamental freedoms. 

Using official **World Bank datasets (1993–2020)**, this project calculates and visualizes the statistical probability of an individual being born into any given nation over the past three decades.

## ✨ Key Features
* **Data Processing:** Cleans and aggregates global population and crude birth rates for all nations.
* **Probability Modeling:** Computes each country’s exact share of global births per year.
* **Interactive Mapping:** Uses **Plotly Express** to build animated choropleth maps with timeline sliders.

## 📂 Repository Structure
```text
BirthAtlas/
├── data/
│   ├── raw/                 # Raw World Bank CSV datasets
│   └── processed/           # Computed birth probability dataset
├── notebooks/
│   ├── 01_process_data.ipynb # Data cleaning and merging pipeline
│   └── 02_visualize.ipynb    # Plotly map generation
├── index.html               # The interactive map (Live Demo)
├── requirements.txt         # Python dependencies
└── README.md                # This file