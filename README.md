# 📰 CPJ Database Cleanning
![Status](https://img.shields.io/badge/Status-Completed-green)

Comprehensive data cleaning and exploratory analysis of the CPJ (Committee to Protect Journalists LINK: https://cpj.org/) global database on journalist deaths.

> **Note:** This project is primarily intended to showcase an ETL pipeline (Extract, Transform, Load) rather than to be a reusable tool. The notebook documents the cleaning decisions made for this specific dataset.

## Description

This project was born out of a gap identified during the module **"Information Visualisation - CS5044"** that I attended at the University of St Andrews. The CPJ database was provided without a cleaning phase, so I built one with three goals:

1. Develop a solid understanding of the dataset structure and content. 
2. Clean and prepare the file provided by the professor (missing values, duplicates, inconsistencies).
3. Verify the integrity of the cleaned output against the official CPJ methodology.

---

## How to use?

```bash
# Clone the repo
git clone https://github.com/AlexandrePuiseux65/CPJ-Cleaning-database.git
cd CPJ-Cleaning-database
```

You can add your own version of the CPJ database in `raw_data/` and run the Jupyter Notebook in the `analysis/` folder. However, the project was built around a specific version of the dataset, so I recommend using the one provided in `raw_data/`.

## Authors
* [@Alexandre Puiseux](https://github.com/AlexandrePuiseux65)

# Acknowledgments

## Dataset
> CPJ — *Committee to Protect Journalists Database & Methodology*  
> https://cpj.org/data/methodology/

