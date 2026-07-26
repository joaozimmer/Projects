# San Francisco Housing Market Analysis (2005)

## Overview
This repository contains an **Exploratory Data Analysis (EDA)** of real estate transactions in the San Francisco Bay Area, focusing strictly on properties sold in the year **2005**. 

The project aims to uncover market trends, price distributions, and geographical correlations using Python data science libraries.

## Pipeline & Key Features
- **Data Preprocessing & Cleaning:** Handled missing values, formatted datetime variables, and isolated the year 2005 subset.
- **Statistical Profiling:** Generated descriptive statistics for parametric evaluation of property prices, square footage, and room counts.
- **Data Visualization:** Built advanced plots using **Matplotlib** and **Seaborn**:
  - Price distribution histograms (with KDE).
  - Bivariate scatter plots analyzing building square footage vs. sale price.
  - Boxplots displaying price dispersion and outliers across different counties.
- **Geospatial Enrichment:** Merged local postal codes with public government coordinate datasets to plot a spatial distribution map styled with cartographic tile layers via **Contextily** and **Geopandas**.

## Technologies Used
- **Python** (Pandas, NumPy)
- **Data Visualization:** Matplotlib, Seaborn
- **Geospatial Analysis:** Geopandas, Contextily, Shapely

## How to Run
1. Clone this repository:
   
      **git clone** https://github.com/joaozimmer/Projects.git

   1) Ensure dependencies are installed:
   pip install pandas matplotlib seaborn geopandas contextily shapely

   2) Important Note on File Path:
   Make sure the dataset file (data_san_francisco.txt) is in your working directory, and update the file_path variable in the script to point to it correctly.

   3)Run the script to generate the statistical insights and visualizations.
