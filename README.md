# COVID-19-Global-Data-Tracker-Project
---

# 🦠 COVID-19 Global Data Tracker

A data analysis project to explore, visualize, and report on global COVID-19 trends using real-world data. This Jupyter Notebook tracks cases, deaths, recoveries, and vaccination progress across multiple countries over time.

## 📌 Project Overview

This project helps learners and data analysts:

* Import and clean global COVID-19 data
* Analyze time trends in cases, deaths, and vaccinations
* Compare metrics across selected countries
* Visualize key insights using line plots, bar charts, and choropleth maps
* Communicate findings with narrative markdown

## 🔍 Data Source

* **[Our World in Data - COVID-19 Dataset](https://github.com/owid/covid-19-data/tree/master/public/data)**

  * Download: `owid-covid-data.csv`

## 🧰 Tools Used

* Python 3
* Jupyter Notebook
* pandas
* matplotlib
* seaborn
* plotly (optional for choropleth maps)

## 🚀 Getting Started

### Prerequisites

Make sure you have the following installed:

* Python 3.7+
* pip
* Jupyter Notebook or VS Code with Jupyter extension

### Installation

```bash
pip install pandas matplotlib seaborn plotly
```

### Running the Notebook

1. Clone this repository or download the `.ipynb` file.
2. Download `owid-covid-data.csv` from [Our World in Data](https://github.com/owid/covid-19-data/tree/master/public/data).
3. Save the CSV in the same folder as your notebook.
4. Launch Jupyter Notebook:

```bash
jupyter notebook
```

5. Open `COVID19_Global_Data_Tracker.ipynb` and run the cells step-by-step.

## 📊 Features

* Track COVID-19 trends for selected countries (e.g., Kenya, USA, India)
* Compare vaccination rollouts
* Compute and visualize death rates over time
* Optional choropleth map to visualize cases globally

## 🧠 Insights

* 📈 *India experienced a steep second wave in mid-2021.*
* 💉 *The U.S. had a faster vaccine rollout compared to Kenya.*
* ⚠️ *Death rates peaked during major case surges.*
