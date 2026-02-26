# ⚽ Football Fans Impact Analysis

## Overview

This project analyzes the impact of football fans on team performance, home advantage, and league dynamics using data collected from multiple top football leagues.

The project includes a full data pipeline:

* web scraping
* data cleaning
* feature engineering
* statistical analysis
* clustering
* advanced visualization

The goal is to understand whether stadium attendance influences team performance and league economics.

---

## Project Pipeline

### 1️⃣ Web Scraping & Data Collection

Data was collected from:

* https://www.transfermarkt.pl/

The scraping pipeline collects:

* stadium attendance
* stadium capacity and utilization
* match results
* goals scored and conceded
* home performance statistics
* financial transfer activity

The pipeline:

* scrapes multiple leagues
* crawls club pages to retrieve full club names
* merges attendance and performance tables
* cleans inconsistent club names
* generates final analysis dataset

Output dataset:

* `Analiza.csv`

---

### 2️⃣ Data Processing

* data merging
* missing value handling
* feature engineering
* scaling and normalization
* dataset integration across leagues and seasons

---

### 3️⃣ Statistical Analysis

* correlation analysis
* hypothesis testing
* performance metrics analysis

---

### 4️⃣ Machine Learning

* K-means clustering of team performance
* grouping teams into performance categories

---

### 5️⃣ Visualization

* ggplot visualizations
* animated charts
* interactive plots
* correlation heatmaps
* geospatial visualization
* radar charts
* 3D visualizations

---

## Research Questions

* Do fans influence team performance?
* Does attendance correlate with wins?
* How did COVID affect home advantage?
* What distinguishes strong vs weak home teams?
* Does attacking performance impact results more than defense?
* Do fans influence league financial activity?

---

## Data Coverage

Leagues analyzed:

* Premier League
* Bundesliga
* LaLiga
* Serie A
* Ligue 1
* Eredivisie
* Liga Portugal
* Jupiler Pro League
* Ekstraklasa
* Campeonato Brasileiro Série A

Seasons:

2012/2013 – 2023/2024

---

## Project Structure

```
scraping/
    data_scraping.Rmd
analysis/
    football_analysis.Rmd
data/
    *.csv
reports/
    *.html
```

---

## Technologies

* R
* rvest (web scraping)
* Rcrawler (web crawling)
* tidyverse
* ggplot2
* plotly
* gganimate
* leaflet
* factoextra
* ggcorrplot

---

## Key Findings

* Attendance correlates with team performance.
* Home advantage decreased during COVID season.
* Higher attendance relates to higher financial activity.
* Teams can be grouped into performance clusters.
* Offensive performance shows stronger relation to points than defensive performance.

---

## Author

Igor Rybinski
