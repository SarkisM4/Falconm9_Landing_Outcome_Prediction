# Predictive Analytics for Falcon 9 First Stage Landing Success

## Project Background and Context
- Space X advertises Falcon 9 rocket launches on its website with a cost of 62 million dollars; other providers cost upward of 165 million 
  dollars each, much of the savings is because Space X can reuse the first stage. Therefore, if we can determine if the first stage will 
  land, we can determine the cost of a launch. This information can be used if an alternate company wants to bid against space X for a 
  rocket launch. This goal of the project is to create a machine learning pipeline to predict if the first stage will land successfully.

### Problems to Answers
- What factors determine if the rocket will land successfully?
- The interaction amongst various features that determine the success rate of a successful landing?
- What operating conditions needs to be inplace to ensure a successful landing program?

### Executive Summary
- Data collection methodology:
- Data was collected using SpaceX API and web scraping from Wikipedia.
- Perform data wrangling
- One-hot encoding was applied to categorical features
- Perform exploratory data analysis (EDA) using visualization and SQL
- Perform interactive visual analytics using Folium and Plotly Dash
- Perform predictive analysis using classification models
- How to build, tune, evaluate classification models
