![header](https://capsule-render.vercel.app/api?type=waving&color=gradient&height=250&section=header&text=IMDB%20Movies%20EDA&fontSize=50&animation=fadeIn)

<div align="center">
  <a href="https://git.io/typing-svg"><img src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=600&size=24&duration=3000&pause=1000&color=36BCF7&center=true&vCenter=true&width=800&lines=Exploratory+Data+Analysis;Extracting+Business+Insights;Data+Cleaning+%26+Visualization" alt="Typing SVG" /></a>
</div>

<p align="center">
  <img src="https://img.shields.io/badge/Python-3.8%2B-blue" />
  <img src="https://img.shields.io/badge/Pandas-Data%20Analysis-150458" />
  <img src="https://img.shields.io/badge/Data%20Visualization-Seaborn-4EABB3" />
  <img src="https://img.shields.io/badge/EDA-Exploratory%20Data%20Analysis-orange" />
</p>

> **End-to-end Exploratory Data Analysis (EDA)** on a comprehensive **19,800+ movies dataset**, utilizing Python and Pandas to extract actionable business insights.  
> This repository demonstrates a rigorous approach to **data cleaning, data type conversion, exploratory analysis, and visualization**, highlighting the transition from raw datasets to structured decision-making frameworks.


## 1. Project Significance 

This analysis showcases core analytical competencies required for quantitative and data science roles:
- Executing complex data cleaning operations on large, unstructured datasets (e.g., parsing strings into continuous numerical formats).
- Designing and answering objective, **business-driven analytical queries**.
- Utilizing **Pandas** for efficient data manipulation, aggregation, and boolean filtering.
- Presenting findings through clear, data-driven visual representations.
- Maintaining clean, optimized, and reproducible code structures.

<img src="https://user-images.githubusercontent.com/1303154/88677602-1635ba80-d120-11ea-84d8-d263ba5fc3c0.gif" width="100%">

## 2. Dataset Overview

- **Size:** 19,808 records
- **Features:** Movie Title, Year, Rating, Certificate, Duration, Genre, Votes, Gross Income, Director(s), and Stars.
- **Objective:** To conduct both descriptive and diagnostic analytics, uncovering underlying statistical trends within the cinematic industry.

<img src="https://user-images.githubusercontent.com/1303154/88677602-1635ba80-d120-11ea-84d8-d263ba5fc3c0.gif" width="100%">

## 3. Analytical Scope & Key Questions

The notebook tackles structured analytical problems, progressing from foundational data cleaning to advanced business strategy formulation. Key areas explored include:

**Data Preprocessing & Structuring:**
- Standardizing numerical columns (e.g., converting `175 min` to `175`, stripping currency symbols and commas from gross income).
- Handling missing data and assessing dataset integrity.

**Exploratory & Business Questions:**
- **Hidden Gems & Overhyped Films:** Filtering for high-rating/low-vote and low-rating/high-gross intersections.
- **Industry Trends:** Mapping the volume of movie releases and average ratings across decades.
- **Revenue Drivers:** Analyzing the correlation between vote counts, duration, and gross income.
- **The Sequel Effect:** Quantifying the financial impact of having numerical sequences in movie titles.
- **The Ultimate Business Decision:** Determining the optimal movie genre to fund based on average rating and average gross income metrics.

<img src="https://user-images.githubusercontent.com/1303154/88677602-1635ba80-d120-11ea-84d8-d263ba5fc3c0.gif" width="100%">

## 4. Tools & Technologies

**Languages & Libraries**
- **Python 3**
- **Pandas** (Data Manipulation, Groupby, Aggregation)
- **Matplotlib & Seaborn** (Data Visualization)

**Core Methodologies**
- Exploratory Data Analysis (EDA)
- Data Cleansing & Type Conversion
- Statistical Correlation Analysis
- Insight Generation for Business Strategy

<img src="https://user-images.githubusercontent.com/1303154/88677602-1635ba80-d120-11ea-84d8-d263ba5fc3c0.gif" width="100%">

## 5. Key Visualizations

- Time-series analysis of the average rating trend over the years.
- Histograms and distribution plots depicting the frequency of movie ratings.
- Statistical summaries representing director hit rates and genre-based revenue averages.

<img src="https://user-images.githubusercontent.com/1303154/88677602-1635ba80-d120-11ea-84d8-d263ba5fc3c0.gif" width="100%">

## 6. Repository Structure

```text
📁 IMDB-Data-Analysis/
│
├── IMDB_Project.ipynb        # Core analysis and visualization notebook
├── README.md                 # Project documentation
└── data/
    └── movies.csv            # Raw dataset
