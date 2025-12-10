Final Project — Coffee Quality Analysis

This repository contains the final project for BIOS 512.
The goal of this project is to analyze coffee quality evaluation data from the Coffee Quality Institute (CQI), focusing on flavor attributes, processing methods, and country-level differences.
All analysis is performed in R using a Jupyter Notebook (.ipynb), as required by the course guidelines.

1. Data Source

The raw data used in this project originates from the Coffee Quality Institute (CQI) Coffee Quality Database.
I obtained the data from a publicly mirrored GitHub repository (no login required):

GitHub Mirror of CQI Dataset:
🔗 https://github.com/jldbc/coffee-quality-database

From these files, I created the raw dataset versions included in this repository:

arabica_ratings_raw.csv

robusta_ratings_raw.csv

After additional preprocessing in the Notebook, I produced:

coffee_clean.csv (cleaned dataset used for analysis)

2. Project Objectives

This project applies the three analytical methods:
Dimensionality Reduction (PCA)
Clustering (K-means)
Regression (Linear Regression)
The analysis focuses on understanding what factors contribute to variation in coffee quality scores.

3. Research Questions
RQ1 — Clustering (B)
Can coffee samples be grouped into distinct flavor-based clusters using quantitative cupping attributes?

RQ2 — Processing Method Differences (C)
Do different processing methods (Washed, Natural, Honey) exhibit systematic differences in flavor attributes or total cup points?

RQ3 — Country Differences (D)
Are there meaningful differences in flavor attributes or overall quality across countries of origin?

4. How to Run the Notebook
This project uses:
R (tidyverse, ggplot2, broom, cluster, factoextra, etc.)
Jupyter Notebook with R kernel
Binder/GitHub 
Simply open final_project.ipynb in Jupyter and run all cells.
