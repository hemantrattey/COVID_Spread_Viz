# COVID-19 Data & Visualization


## Data Collection, Processing and Visualization

This project is a basic data cleaning and analysis project using Pandas for data cleaning and pre processing and using Plotly to build choropleth maps and animations. Below are the detailed steps mentioned for the analysis.  

### Exploring the Dataset

This dataset is provided by the amazing team at [John Hopkins University Center for Systems Science and Engineering (CSSE)](https://systems.jhu.edu/). The dataset used in this project can be found at this [link](https://raw.githubusercontent.com/datasets/covid-19/master/data/countries-aggregated.csv). This data is updated daily, hence I'll just use the link directly to read the csv instead of downloading it again and again. 

We start by reading the csv file into a *Pandas DataFrame*. Since we are directly using the link to the csv file, everytime the notebook is run, the latest updated data will be used.  

