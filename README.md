# 🎬 IMDb Movie Ratings – Exploratory Data Analysis (EDA)

## 📌 Project Overview

This project focuses on analyzing **IMDb Top 500 movies** to uncover **patterns, trends, and insights** in ratings, revenues, and directors’ success.
The data was collected via **web scraping** (Selenium + BeautifulSoup) and analyzed using **EDA techniques** (univariate, bivariate, and multivariate analysis).


---

## 🎯 Objective

* **Goal**: Analyze IMDb movie ratings to uncover meaningful audience and industry insights.
* **Approach**: Use web scraping to collect data and apply advanced EDA for trends & patterns.

---

## 🌐 Web Scraping

* **Website Used**: [IMDb](https://www.imdb.com/)
* **Tools**:

  * **Selenium** – Automates browser for dynamic content scraping.
  * **BeautifulSoup** – Parses HTML to extract structured data.
* **Data Scope**: Top 500 movies ranked by IMDb ratings.

---

## 🧹 Data Cleaning

* Converted **runtime hours → minutes** for easier analysis.
* Standardized **figures in millions/thousands → numerical values**.
* Handled missing values by replacing with **mean values**.

---

## 📊 Data Analysis

### 🔹 Univariate Analysis

* Most ratings fall between **6–8**, peaking around **7**.
* Ratings are **left-skewed**, showing a bias toward positive reviews.
* **Density & histogram plots** confirm clustering around 6.5–7.

### 🔹 Bivariate Analysis

* **James Cameron** leads in total gross %, followed by **Steven Spielberg**.
* Directors like **Anthony Russo, Peter Jackson, and David Yates** also dominate box office success.

### 🔹 Multivariate Analysis

* **Peter Jackson (Lord of the Rings)** and **George Lucas (Star Wars)** lead top-rated franchises.
* **Christopher Nolan** has multiple high-rated movies, proving consistent audience appeal.
* Insights show strong audience preference for **established directors & franchises**.

---

## 🛠 Tools & Libraries

* **Python** – Core language
* **Selenium, BeautifulSoup** – Web scraping
* **Pandas, NumPy** – Data cleaning & manipulation
* **Matplotlib, Seaborn** – Data visualization

---

## 📑 Conclusion

* IMDb ratings show a clear audience bias toward **moderately high scores (6–8)**.
* **Directors and franchises** (e.g., Jackson, Lucas, Cameron, Nolan) dominate top-rated films.
* Data-driven insights from ratings, runtime, and release trends can help **filmmakers & studios** in:
  ✔ Content creation strategies
  ✔ Marketing decisions
  ✔ Audience engagement optimization


---

## 🔗 How to Run

1. Clone the repository.
2. Run the scraper with Selenium to fetch IMDb data.
3. Use the provided Jupyter Notebook (`IMDb_EDA.ipynb`) for cleaning & analysis.
4. Explore insights via visualizations.

---
