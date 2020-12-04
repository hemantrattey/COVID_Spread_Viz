# COVID-19 Data & Visualization


## Motivation

This project is a basic data cleaning and analysis project using Pandas for data cleaning and pre processing and using Plotly to build choropleth maps and animations. The main aim of this project is to look at how COVID-19 spread across the world and also figure out if lockdowns imposed by Governments was impactful in controlling the number of cases or not. For analysing the lockdown impact, I will only be looking at confirmed cases in India.    

### Dataset

This dataset is provided by the amazing team at [John Hopkins University Center for Systems Science and Engineering (CSSE)](https://systems.jhu.edu/). The dataset used in this project can be found at this [link](https://raw.githubusercontent.com/datasets/covid-19/master/data/countries-aggregated.csv). This data is updated daily, hence I'll just use the link directly to read the csv instead of downloading it again and again. 

### Exploring the Dataset

We start by reading the csv file into a *Pandas DataFrame*. Since we are directly using the link to the csv file, everytime the notebook is run, the latest updated data will be used. 

Upon printing the first 5 rows using the head() method, we see that the data starts at 22<sup>nd</sup> January 2020 and the data is aggregated by the countries. The columns are Date, Country, Confirmed, Recovered and Deaths which are self explanatory. 

Since we are concerned with looking at how the cases spread over time, we will only select rows where number of confirmed cases is more than 0. 

### Plotting Choropleth Map

I used the Plotly Express library to plot the Choropleth animation. The documentation can be found [here].(https://plotly.com/python-api-reference/plotly.express.html)

I couldn't find a way to export the animation using the plotly library hence I'll upload a MP4 file seperately. 