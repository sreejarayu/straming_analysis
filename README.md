# straming_analysis
Comparative analysis of streaming platforms to understand content distribution, genres, and growth trends using Python, Pandas, and Power BI.
# Streaming Platform Content Strategy Analysis

## Project Overview

This project performs a comprehensive comparative analysis of major streaming platforms — **Netflix, Amazon Prime Video, Disney+, and Hulu** — to understand differences in content strategy, genre distribution, geographic production, and growth trends.

The objective is to derive actionable insights that can support **content acquisition, platform positioning, and marketing strategies** in the competitive streaming industry.

---

## Business Problem

Streaming platforms invest heavily in content but differ in their strategic focus. This project aims to answer:

* Which platform has the largest content library?
* How do platforms differ in Movies vs TV Shows?
* What genres dominate each platform?
* Which countries produce the most content?
* How has content evolved over time?
* What type of audience does each platform target?

---

## Tools & Technologies

* Python
* Pandas
* Jupyter Notebook
* Power BI (Dashboard - in progress)
* Data Visualization

---

## Dataset

The project combines datasets from four major streaming platforms:

* Netflix
* Amazon Prime Video
* Disney+
* Hulu

Each dataset includes:

* Content Type (Movie / TV Show)
* Title
* Director and Cast
* Country
* Release Year
* Rating
* Duration
* Genre
* Description

---

## Data Preparation

Key preprocessing steps:

* Standardized column structure across datasets
* Merged multiple datasets into a unified dataset
* Handled missing values (country, rating, duration)
* Converted date columns and extracted `year_added`
* Split multi-genre column using **data explosion technique** for accurate analysis

---

## Key Analysis Areas

### Platform Comparison

* Content distribution across platforms
* Movies vs TV Shows ratio

### Content Strategy

* Genre dominance per platform
* Content rating distribution

### Geographic Insights

* Top content-producing countries
* Global content diversity

### Growth Trends

* Content addition over time
* Platform expansion patterns

---

## Key Insights

* **Netflix** has the largest content library among all platforms
* **Disney+** focuses heavily on family-friendly content (G, PG ratings)
* **Hulu** has a higher proportion of TV shows
* **Amazon Prime Video** offers a diverse mix of international content
* Drama and Comedy are the most dominant genres across platforms
* Content production significantly increased after 2015 across all platforms

---

## Project Structure

streaming-platform-analysis
│
├── data
│   raw datasets (Netflix, Amazon, Disney+, Hulu)
│   cleaned_streaming_data.xlsx
│
├── notebook
│   streaming_analysis.ipynb
│
├── powerbi
│   streaming_dashboard.pbix (in progress)
│
└── README.md

---

## Dashboard 

An interactive Power BI dashboard will be developed to visualize:

* Platform-wise content distribution
* Movies vs TV Shows comparison
* Genre analysis
* Country-wise content production
* Content growth trends

---

## Future Improvements

* Advanced genre clustering
* Recommendation system insights
* User engagement analysis
* Predictive modeling for content trends

---

## Author

Lucky

This project is part of my **Data Analytics Portfolio**, demonstrating skills in data integration, exploratory data analysis, and business intelligence.

---
