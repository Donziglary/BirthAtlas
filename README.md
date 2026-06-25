<<<<<<< HEAD
# 🌍 BirthAtlas: Mapping Birth Probability and Moral Luck

[![Python](https://img.shields.io/badge/Python-3.8%2B-blue.svg)](https://www.python.org)
[![Pandas](https://img.shields.io/badge/Pandas-Data%20Analysis-orange.svg)](https://pandas.pydata.org)
[![Plotly](https://img.shields.io/badge/Plotly-Interactive%20Maps-brightgreen.svg)](https://plotly.com)
=======
🛠 Tech Stack & Tools
Python 3.x

Pandas: Upstream data manipulation, missing value imputation, and feature engineering.

Plotly Express: Creation of high-fidelity, interactive geographical figures equipped with custom hover templates and animation frames.

Jupyter Notebooks: Used as an isolated sandbox environment for granular, step-by-step exploratory data analysis (EDA).
🚀 Getting Started
1. Clone the Repository
2. git clone [https://github.com/Donziglary/BirthAtlas.git](https://github.com/Donziglary/BirthAtlas.git)
cd BirthAtlas
>>>>>>> 0505184ac58435b42006d96a4e64833bb3e04cdf

2. Install Dependencies
It is highly recommended to use an isolated virtual environment (venv or conda):
pip install -r requirements.txt

<<<<<<< HEAD
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
=======
4. Pipeline Execution

    Execute notebooks/01_process_data.ipynb to clean the raw World Bank assets and generate the unified dataset inside data/processed/.

    Execute notebooks/02_visualize.ipynb to generate the interactive visualizations.

    Open index.html directly in any modern web browser to interactively explore the BirthAtlas timeline.

   📈 Analytical Insights & Preview

Note: Run the visualization pipeline and embed a high-resolution screenshot or an animated GIF of the Plotly map here to capture immediate recruiter/reviewer attention.

    💡 Core Narrative: Evaluating the dataset from 1993 to 2020 highlights a massive shift in the global "birth lottery." Due to dropping fertility rates in developed economies, the relative probability of being born in the Global North has steadily contracted. Conversely, geographic luck has concentrated heavily within emerging markets and developing regions (specifically Sub-Saharan Africa and parts of South Asia), opening profound philosophical questions regarding global equity, distributive justice, and resource alloca

    🤝 Contributing

Contributions that expand the analytical depth of this project are welcome. Potential enhancements include overlaying human development indicators (HDI), GDP per capita, or climate vulnerability indexes onto the existing birth luck map. Feel free to open an Issue or submit a Pull Request.

📄 License

This project is licensed under the MIT License. You are free to modify, distribute, and use this software for academic, professional, or commercial applications.
>>>>>>> 0505184ac58435b42006d96a4e64833bb3e04cdf
