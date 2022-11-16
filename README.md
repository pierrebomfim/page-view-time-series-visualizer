[![author](https://img.shields.io/badge/author-pierrebomfim-red.svg)](https://www.linkedin.com/in/carlosfab) [![](https://img.shields.io/badge/python-3.7+-blue.svg)](https://www.python.org/downloads/release/python-365/) [![contributions welcome](https://img.shields.io/badge/contributions-welcome-brightgreen.svg?style=flat)](https://github.com/carlosfab/data_science/issues)

<p align="center">
  <img src="/time-series_banner.png" >
</p>


# Page View Time Series Visualizer

This is a project for FreeCodeCamp.org certificate in Data Analysis w/ Python. 

## Tasks
For this project you will visualize time series data using a line chart, bar chart, and box plots. Using Pandas, Matplotlib, and Seaborn to visualize a dataset containing the number of page views each day on the freeCodeCamp.org forum from 2016-05-09 to 2019-12-03. The data visualizations will help you understand the patterns in visits and identify yearly and monthly growth.

- Use Pandas to import the data from "fcc-forum-pageviews.csv". Set the index to the date column.
- Clean the data by filtering out days when the page views were in the top 2.5% of the dataset or bottom 2.5% of the dataset.
- Create a draw_line_plot function that uses Matplotlib to draw a line chart similar to "examples/Figure_1.png". The title should be Daily freeCodeCamp Forum Page Views 5/2016-12/2019. The label on the x axis should be Date and the label on the y axis should be Page Views.
- Create a draw_bar_plot function that draws a bar chart similar to "examples/Figure_2.png". It should show average daily page views for each month grouped by year. The legend should show month labels and have a title of Months. On the chart, the label on the x axis should be Years and the label on the y axis should be Average Page Views.
- Create a draw_box_plot function that uses Seaborn to draw two adjacent box plots similar to "examples/Figure_3.png". These box plots should show how the values are distributed within a given year or month and how it compares over time. The title of the first chart should be Year-wise Box Plot (Trend) and the title of the second chart should be Month-wise Box Plot (Seasonality). Make sure the month labels on bottom start at Jan and the x and y axis are labeled correctly. The boilerplate includes commands to prepare the data.

## Directions

Run the Replt boilerplate by [clicking here](https://replit.com/@pierrebomfim/boilerplate-demographic-data-analyzer#main.py)

For development, you can use main.py to test the functions. Click the "run" button and main.py will run.

Unit tests are written under test_module.py. It's imported from test_module.py to main.py for your convenience. The tests will run automatically whenever you hit the "run" button.

## FreeCodeCamp instructions for the project
[Click here](https://www.freecodecamp.org/learn/data-analysis-with-python/data-analysis-with-python-projects/page-view-time-series-visualizer
)
