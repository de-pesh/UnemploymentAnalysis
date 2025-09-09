# Unemployment Analysis in India

This project analyzes the unemployment trends in India using a dataset that captures various employment metrics. The goal is to visualize the data and gain insights into how factors such as the estimated unemployment rate, employed population, and labor participation rate are correlated.

### Table of Contents

-	Project Overview
-	Dataset
-	Installation
-	Project Structure
-	Visualization
-	Correlation Analysis
-	Conclusion

### Project Overview

This project involves analyzing employment-related data in India to identify patterns and trends. The analysis is done through:

-	Data cleaning and preprocessing
-	Visualization of key metrics
-	Heatmaps for correlation between variables

The analysis helps in understanding the unemployment rate, the number of employed people, and the labor participation rate.

## Dataset

The project uses the following data files:
- data/Unemployment in India.csv: Main dataset with employment metrics by region and date.
- data/Unemployment_Rate_upto_11_2020.csv: Additional dataset for extended analysis (not used in the main notebook).

## Installation

1. Clone the repository:
```bash
   git clone https://github.com/de-pesh/UnemploymentAanalysis.git
   cd UnemploymentAnalysis
```
2. (Recommended) Create and activate a virtual environment:
```bash
   python -m venv venv
   source venv/bin/activate  # On Windows use venv\Scripts\activate
```
3. Install the required dependencies:
```bash
pip install -r requirements.txt
```
4. Make sure you have Jupyter Notebook installed to run the .ipynb file.

## Project Structure

- unemployment.ipynb: The Jupyter notebook containing the code for data analysis and visualization.
- requirements.txt: Contains the list of Python dependencies needed to run the project.
- data/Unemployment in India.csv: Main dataset.
- data/Unemployment_Rate_upto_11_2020.csv: Additional dataset.

## Visualization

Sample outputs and visualizations are available in the notebook (unemployment.ipynb).

The project uses the following visualization techniques:

-	Line Plots: To show the unemployment trend over time.
-	Bar Charts: To compare employment metrics between different regions.
-	Heatmaps: To visualize the correlation between the unemployment rate, employed individuals, and labor participation rate.

## Correlation Analysis

A correlation matrix is generated to understand the relationship between the key variables in the dataset. The heatmap visualization helps in identifying strong or weak correlations, which provides insights into how these employment factors influence each other.

## Conclusion

This project aims to understand key employment trends in India, offering insights into how various factors related to unemployment and labor participation are correlated. The visualizations provide a clearer picture of the data, making it easier to identify patterns and trends.
