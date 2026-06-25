# 🌍 BirthAtlas

### Exploring the Global Birth Lottery Through Data

[![Python](https://img.shields.io/badge/Python-3.8%2B-blue.svg)](https://www.python.org)
[![Pandas](https://img.shields.io/badge/Pandas-Data%20Analysis-orange.svg)](https://pandas.pydata.org)
[![Plotly](https://img.shields.io/badge/Plotly-Interactive%20Visualization-brightgreen.svg)](https://plotly.com)
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)

## 🚀 Live Demo

Explore the interactive visualization directly in your browser:

👉 **https://donziglary.github.io/BirthAtlas/index.html**

---

## 📖 Overview

BirthAtlas is a data visualization project that explores the probability of being born in different countries around the world.

Using official World Bank demographic datasets, the project estimates annual births for each country and calculates its share of total global births. The results are presented through an interactive animated world map, allowing users to explore how birth distributions change over time.

The project combines demographic analysis, statistical modeling, and geospatial visualization to transform raw population data into an intuitive global perspective.

---

## 💡 Motivation

Every person is born into circumstances they never chose.

BirthAtlas explores this idea quantitatively through a simple question:

> If a newborn were selected at random from all births worldwide, in which country would that child most likely have been born?

This concept is closely related to the philosophical idea of the **Birth Lottery**, highlighting how place of birth can influence opportunities, living conditions, and life outcomes.

---

## ✨ Features

* Global birth probability estimation for each country
* Interactive choropleth world map
* Animated timeline visualization
* Country-level ranking system
* Detailed hover tooltips with demographic statistics
* Standalone HTML deployment
* Fully browser-based experience

---

## 📊 Methodology

For each country and year:

```text
Births = Population × Birth Rate / 1000

Birth Probability (%) =
(Country Births / Global Births) × 100
```

Where:

* Population data is obtained from the World Bank
* Birth Rate represents annual births per 1,000 inhabitants
* Global Births is the total estimated number of births worldwide for a given year

The resulting probability represents a country's share of all births occurring globally during that year.

---

## 🌐 Interactive Visualization

The final output is an interactive Plotly choropleth map featuring:

* Global geographic visualization
* Timeline slider
* Dynamic color scaling
* Country-level demographic insights
* Animated exploration of birth probabilities across years

Try it here:

👉 **https://donziglary.github.io/BirthAtlas/index.html**

---

## 📂 Repository Structure

```text
BirthAtlas/
│
├── data/
│   ├── raw/
│   │   ├── pop_total.csv
│   │   └── birth_rates.csv
│   │
│   └── processed/
│       └── birth_probability.csv
│
├── notebooks/
│   ├── 01_process_data.ipynb
│   └── 02_visualize.ipynb
│
├── index.html
├── requirements.txt
├── .gitignore
└── README.md
```

---

## 🛠 Technologies

* Python
* Pandas
* NumPy
* Plotly
* Jupyter Notebook

---

## 🌍 Data Sources

* World Bank Population Dataset
* World Bank Crude Birth Rate Dataset

---

## 🔮 Future Development

Potential future improvements include:

* Birth probability forecasting using machine learning
* Regional and continental analysis
* Additional demographic indicators
* Interactive dashboard enhancements
* Historical trend comparison tools
* Integration of socioeconomic indicators

---

## 📄 License

This project is released under the MIT License.
