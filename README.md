# Time Series Visualizer

## Overview
The Time Series Visualizer project is designed to visualize time series data using line charts, bar charts, and box plots. This project utilizes Pandas, Matplotlib, and Seaborn to visualize the number of page views each day on the freeCodeCamp.orgforum from 2016-05-09 to 2019-12-03. The visualizations help to understand patterns in visits and identify yearly and monthly growth trends.

## Features
- Multiple Visualizations: Generate line plots, bar charts, and box plots to represent time series data.
- Customization Options: Customize the plots with various parameters such as colors, labels, and more.
- Data Filtering: Filter data by specific time frames or conditions to focus on relevant trends.
- Prediction Capability: Visualize line plot to generate trends over time.

## Usage
1. Import Data: The data is imported from "fcc-forum-pageviews.csv" and the index is set to the date column.
2. Clean Data: Filter out days with page views in the top and bottom 2.5% to remove outliers.
3. Generate Visualizations: Use the provided functions to create the visualizations.

## Analysis Result
### Bar Plot
![bar plot](https://github.com/OfficialAlok/TimeSeriesVisualizer/blob/main/barplot.png?raw=true)

### Line Plot
![line plot](https://github.com/OfficialAlok/TimeSeriesVisualizer/blob/main/lineplot.png?raw=true)

### Box Plot
![box plot](https://github.com/OfficialAlok/TimeSeriesVisualizer/blob/main/box-plot.png?raw=true)

## Acknowledgments
- Thanks to the creators of Matplotlib, Seaborn, and Pandas for their fantastic libraries.
- Special thanks to freecodecamp.org team.
