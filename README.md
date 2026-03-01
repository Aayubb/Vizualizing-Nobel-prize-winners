# Vizualizing the history of nobel prize winners
![Python](https://img.shields.io/badge/Python-3.x-blue?logo=python&logoColor=white)
![Pandas](https://img.shields.io/badge/Pandas-Data%20Analysis-150458?logo=pandas&logoColor=white)
![Matplotlib](https://img.shields.io/badge/Matplotlib-Visualization-11557c)
![Seaborn](https://img.shields.io/badge/Seaborn-Visualization-4c72b0)
![DataCamp](https://img.shields.io/badge/DataCamp-Project-03EF62?logo=datacamp&logoColor=white)
![Status](https://img.shields.io/badge/Status-Completed-success) 

Exploring a dataset containing a century's worth of Nobel Laureates

> This project is part of the [DataCamp Data Scientist with Python](https://www.datacamp.com/tracks/data-scientist-with-python) career track.

---

## Project Overview
The Nobel Prize is awarded yearly to scientists and scholars in chemistry, literature, physics, medicine, economics, and peace, with the first prize awarded in 1901. This project uses data manipulation and visualization skills to explore the history of this coveted prize.

---

## Analysis Tasks

### 1. Finding out the most commonly awarded gender and country.
### 2. Finding and vizualizing the decade had the highest ratio of US-born Nobel Prize winners to total winners in all categories.
### 3. Finding and vizualizing which decade and Nobel Prize category combination had the highest proportion of female laureates.
### 4. Finding our who was the first woman to receive a Nobel Prize, and in what category.
### 5. Finding out which individuals or organizations have won more than one Nobel Prize throughout the years.

---

## Technologies Used

- **Python 3**
- **pandas** — data loading, filtering, grouping, and aggregation
- **seaborn** - vizualizing data

---

## 📁 Repository Structure

```
├── Nobel prize.ipynb        # Main analysis notebook
├── nobel.csv           # nobel prize dataset
└── README.md
```
---

## Key Concepts Applied

### Data Manipulation with Pandas
Filtering & GroupBy — isolating subsets and aggregating data by decade, category, gender, and birth country to compute counts, ratios, and proportions.
Decade extraction — deriving decade values from year columns using integer arithmetic to enable decade-level trend analysis.
Sorting & peak detection — using value_counts(), sort_values(), and idxmax() to identify top values and maximums across grouped data.
Duplicate detection — identifying repeat Nobel Prize winners by detecting names appearing more than once in the dataset.

### Data Visualization with Seaborn

Categorical & time-series plots — visualizing distributions across gender, category, and birth country, as well as decade-level trends over time.
Plot customization — applying axis labels, titles, and figure sizing for clean, readable charts.

---

## 📄 License

This project is for educational purpose as part of the DataCamp curriculum.
