# Optimizing Bank Marketing - Insight Hackers

This project analyzes bank marketing data to identify key economic indicators and factors influencing subscription rates. It utilizes R for data processing and visualization, alongside Tableau for interactive dashboards.

## Project Structure

- **`Project_Insight_hackers.qmd`**: Quarto document containing the R code for data cleaning, transformation, and visualization.
- **`bank-additional-full.csv`**: The primary dataset used for analysis (Bank Marketing Data Set).
- **`Insight hackers Bi project.twbx`**: Tableau workbook file for interactive visualizations.
- **`economic_indicators_subscription_boxplot.png`**: Generated boxplot visualization of economic indicators.
- **`Project_Insight_hackers.pdf`**: Rendered PDF report of the analysis.

## Key Analysis

The analysis focuses on the relationship between economic variables and the success of marketing campaigns (subscription to term deposits). Key economic indicators analyzed include:

- **Employment Variation Rate (`emp.var.rate`)**
- **Consumer Price Index (`cons.price.idx`)**
- **Consumer Confidence Index (`cons.conf.idx`)**
- **3-Month Euribor Rate (`euribor3m`)**

## Getting Started

### Prerequisites

- **R** and **RStudio**
- **Tableau Desktop** (to view .twbx files)
- **Quarto**

### Required R Packages

```r
install.packages(c("readr", "dplyr", "tidyr", "ggplot2"))
```

### Running the Analysis

1. Open `Project.Rproj` in RStudio.
2. Open `Project_Insight_hackers.qmd`.
3. Render the document to generate the analysis report and visualizations.

## Team - Insight Hackers

Project for ITEC 460 - Spring 2025.
