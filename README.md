# CF_PYTHON_Instacart
**Data analysis for Instacart using Jupyter notebook in the Anaconda environment.**<br>
_Analysis performed for learning purposes with CareerFoundry_

Instacart is an online grocery store that operates through an app. The stakeholders are most interested in the variety of customers in their database along with their purchasing behaviors to implement a **targeted marketing strategy.** 

The goal of the analysis is to perform an initial data exploratory analysis to derive insights and suggest strategies for better segmentation of Instacart shoppers. To learn, a workflow of a typical Python analysis project was mimicked and took me through the preparation process of the data, like cleaning, wrangling, combining, enriching the datasets with new variables, to finally communicate the results through visualizations.

The datasets used for this project contain open-source data from 2017 made available online by Instacart. The consumer data and the prices of the products were both fabricated for learning purposes. Some of the datasets contain over **32M observations.**

The repository contains:
1. Scripts in Jupyter 
1. Report in Excel documenting population flow, consistency checks, wrangled data, derived columns, visualizations, and recommendations.

In this exercise, I worked in **Jupyter**, a file- and library-management system for Python in the Anaconda environment. I mostly used Pandas, NumPy, and Os libraries to conduct data analysis. Later on, I also added other libraries like Matplotlib, Seaborn, and SciPy to plot and visualize the results of my analysis.

For the exploratory analysis, I used the basic functions of head(), tail(), shape, dtypes, columns, or info() to quickly get a summary of info for a dataframe. I also learned to use lists to ignore unnecessary columns when importing the data. For descriptive statistics, the describe() functions helped to spot the first irregularities in the datasets. In the data wrangling process, syntaxes for dropping and renaming columns, changing of data types, transposing the data, and subsetting were applied. In the next steps of data preparation, I performed a consistency check looking for missing values, mixed data types, and duplicates. To perform large-scale manipulations, I learned the concept of combining datasets using procedures like merge, concatenate, or append. In order to draw insights, as excpected by Instacart stakeholders, a further transformation procedures like derriving new columns using if-statements, loc and for-loops functions, as well as grouping and aggregating methods were applied. Finally, for visualizations of my analysis, I used bar charts, horizontally and stacked bar charts, pie charts, line charts, histograms and scatterplots.
