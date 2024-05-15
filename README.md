# us-weather-events-analysis
2024 MLH Global Hack Week: Data | Analyzing US Weather Events Data
## Background
As part of the MLH Global Hack Week, I chose to explore a data set consisting of US weather events. The goal of the analysis was to identify similar states and regions in the US based on weather information and draw related insights.
The Devpost for this project can be found [here](https://devpost.com/software/us-weather-events-data-analysis)!
## Data Overview
This [data set](https://www.kaggle.com/datasets/sobhanmoosavi/us-weather-events/data) contains information on weather events in the US spanning multiple states and cities, sourced from various airport weather stations. The weather events span January 2016 to December 2022 and are quite varied including snow, storms, and other precipitation.
## Usage
- First, download the .ipynb file and the data from the link provided above.
- Set up the appropriate environment to run a Jupyter Notebook file and ensure you have the proper versions of the required libraries.
- Finally, hit "Run All" to execute the analysis and view all output. 
## Summary
K-Means clustering was used to identify similar states based on the percentage of observations of each weather type for each state. For example, the percent of observations of snow, rain, cold, etc. for each state was used to run the clustering analysis. The two plots below provide a summary of how the points are distributed across the clusters:
- The first plot below shows the clusters in a pairplot consisting of each of the engineered features (percentage of each weather type):
  
![Pairplot](https://github.com/gjhaveri98/us-weather-events-analysis/assets/127703784/d4c1bd39-9f54-4d8e-bd4e-9e0483053b93)

- The second plot below shows the clusters in a scatterplot based on the approximate latitude and longitude of each of the states in the data set:
  
![Scatterplot](https://github.com/gjhaveri98/us-weather-events-analysis/assets/127703784/5d42957c-d2cd-44c3-82a4-43d34aee19ed)




