# 📊 Page View Time Series Visualizer

Visualize daily page views of the **freeCodeCamp.org forum** (2016-05-09 to 2019-12-03) using Python. This project demonstrates trends, seasonality, and patterns through **line plots, bar charts, and box plots**.

---

## 🔗 Dataset

The project uses the dataset [`fcc-forum-pageviews.csv`](https://raw.githubusercontent.com/freeCodeCamp/boilerplate-page-view-time-series-visualizer/main/fcc-forum-pageviews.csv) with the following columns:

- `date` – Date of page views  
- `value` – Number of page views  

> Place the CSV in the root folder of the project.

---

## ⚡ Features

- **Line Plot** – Shows daily page views over time.  
- **Bar Plot** – Displays monthly average page views grouped by year.  
- **Box Plot** – Compares distributions year-wise (trend) and month-wise (seasonality).  
- **Data Cleaning** – Filters out outliers (top 2.5% and bottom 2.5% of page views) for accurate visualization.

---

## 🛠️ Installation

1. Clone the repository:

```bash
git clone <your-repo-url>
cd <repo-folder>
````

2. Install required Python packages:

```bash
pip install pandas matplotlib seaborn
```

---

## 🚀 Usage

Run the visualizer functions to generate plots:

```bash
python main.py
```

The following images will be saved in the project folder:

* `line_plot.png`
* `bar_plot.png`
* `box_plot.png`

---

## 📈 Plots Overview

1. **Line Plot** – Daily page views from May 2016 to December 2019.
2. **Bar Plot** – Monthly averages grouped by year, highlighting seasonal trends.
3. **Box Plot** –

   * **Year-wise**: Trend across years.
   * **Month-wise**: Seasonal patterns (Jan–Dec).

---

## 🖥️ Technologies Used

* Python 3
* Pandas
* Matplotlib
* Seaborn

---

## 📝 License

This project is open-source under the **MIT License**.
Feel free to modify, reuse, and share.

---
