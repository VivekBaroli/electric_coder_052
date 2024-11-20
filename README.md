Flipkart Product Analysis

[View Deployed Dashboard]([https://app.powerbi.com/view?r=eyJrIjoiOWVmMjcwYzEtZGQ3Yi00NjYxLWJiYzctNWYxZGNmZTk4ODRlIiwidCI6ImM0ODg3MzRiLTljMDAtNDBjZC04YjMyLWE3NGQyZTE5OGI5NiJ9](https://app.powerbi.com/view?r=eyJrIjoiODI1M2E0YjQtODIzYi00MzcyLTkzMTAtNjkwZDg2MmVmZTZlIiwidCI6ImM0ODg3MzRiLTljMDAtNDBjZC04YjMyLWE3NGQyZTE5OGI5NiJ9))

- [Overview](#overview)
- [Project Workflow](#project-workflow)
  - [Data Collection](#data-collection)
  - [Data Cleaning](#data-cleaning)
  - [Data Visualization](#data-visualization)
- [Outcome](#outcome)
- [Requirements](#requirements)
- [Installation](#installation)
- [Completed Enhancements](#completed-enhancements)

---

## Overview

This project involves scraping, cleaning, and visualizing product data from Flipkart to provide valuable insights into market trends, pricing, and customer ratings. The project utilizes Selenium for web scraping, Python (with Pandas and NumPy) for data cleaning and transformation, and Power BI for creating an interactive dashboard.

The analysis covers a sample of 72,000 product data points, including product names, prices, ratings, and categories, from Flipkart's online store.

---

## Project Workflow

The project follows a structured process with three main steps:

### Data Collection

- **Tool Used:** Selenium  
- **Description:** Product data was scraped from Flipkart using Selenium. The scraped data includes various attributes such as product names, prices, ratings, and categories. The process ensures that the data is collected dynamically from the Flipkart website for real-time insights.

### Data Cleaning

- **Tools Used:** Python (Pandas, NumPy)  
- **Description:** Once the data was scraped, it was cleaned and processed to ensure consistency and accuracy. The cleaning steps involved:
  - Handling missing values and duplicates.
  - Normalizing data formats (e.g., prices, ratings).
  - Ensuring that data types were appropriate for further analysis.

### Data Visualization

- **Tool Used:** Power BI  
- **Description:** After the data was cleaned, it was imported into Power BI for visualization. The final output is an interactive dashboard that provides key insights into the product data, including:
  - **Product Distribution by Category:** A breakdown of products across different categories.
  - **Price and Rating Analysis:** A comparison of product prices and ratings.
  - **Top-Rated Products:** Identification of top-rated products based on customer reviews.
  - **Popularity Distribution:** Insights into how popular products are based on customer ratings and reviews.

---

## Outcome

The final Power BI dashboard allows users to explore the product data interactively, providing a deeper understanding of the market trends, pricing strategies, and customer preferences. The dashboard offers a user-friendly interface to view data in various formats, such as charts, graphs, and tables, making it easy to derive actionable insights for business or research purposes.

---

## Requirements

- **Python 3.x**  
  - Pandas  
  - NumPy  
  - Selenium  
- **Power BI Desktop** for the visualization component  
- **WebDriver** for Selenium (e.g., ChromeDriver)

---

## Installation

1. Clone the repository or download the project files.
2. Install required Python libraries:
   ```bash
   pip install pandas numpy selenium
   ```
3. Set up Selenium WebDriver (e.g., ChromeDriver) and ensure it's accessible in your system's PATH.
4. Run the Python script to scrape data from Flipkart:
   ```bash
   python scrape_flipkart.py
   ```
5. After scraping, use the cleaned data to load it into Power BI for visualization.

---

## Completed Enhancements

- **Automated Data Scraping:** Implemented automation to regularly scrape the latest product data from Flipkart.
- **Extended Data Attributes:** Expanded the dataset to include more granular product attributes for deeper analysis (e.g., product eatures, Popularity Distribution).
- **Advanced Power BI Features:** Enhanced the Power BI dashboard with dynamic filtering options, drill-down capabilities, and improved visualizations to provide users with more interactive and insightful data exploration.

---
