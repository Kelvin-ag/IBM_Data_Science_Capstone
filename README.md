# IBM Data Science Capstone
![](https://github.com/Kelvin-ag/IBM_Data_Science_Capstone/blob/main/Screenshot%202026-03-02%20at%2022.30.14.png)
## Project Overview
Space X advertises Falcon 9 rocket launches on its website with a cost of 62 million dollars; other providers cost upward of 165 million dollars each, much of the savings is because Space X can reuse the first stage.<br>Therefore if we can determine if the first stage will land, we can determine the cost of a launch. This information can be used if an alternate company wants to bid against space X for a rocket launch.
## Problems to answer
- Find correlations between rocket features and success landing rate
- Predict if the Falcon 9 first stage will land successfully
## Summary of methodologies
- Data collection
- Data wrangling
- EDA with SQL  
- Data Visualization with Dash
- Geospatial analysis with Folium
- Predictive analysis
## Summary of results
- Interactive Dashboard with Plotly
- EDA analytics results
- Predictive analytics results using classification models
# Repository Structure
### Data Collection (not included in repo)
1. Requests made to SpaceX API 
2. Data scraped from SpaceX Wiki page
### Notebooks
1.[Data collection](spacex_data_collection.ipynb)<br>
2.[Data scraping](webscraping.ipynb)<br>
3.[Data Wrangling](Data_wrangling.ipynb)<br>
4.[EDA with SQL](eda.ipynb)<br>
5.[Data Visualization](dataviz.ipynb)<br>
6.[Geospatial analysis with Folium](site_location.ipynb)<br>
7.[Predictions](Prediction.ipynb)<br>
## Results
### Exploratory data analysis results
- Analyzing the results shows that heavier payload have a higher success rate than lighter ones
- The results also show that success rate has been increasing yearly
### Predictive analysis results
Comparing the accuracy of the four classification models, all return the same accuracy of about 83% for test data.
### Conclusions
- As the number of flights increased, the success rate increased, and recently it has exceeded 80%.
- Orbital types SSO, HEO, GEO, and ES-L1 have the highest success rate (100%).
- The launch site is close to railways, highways, and coastline, but far from cities.
- KSLC-39A has the highest number of launch successes and the highest success rate among all sites.
- The launch success rate of low weighted payloads is higher than that of heavy weighted payloads.
- The best performing classification model is the Decision Tree model
## Tools and Libraries
- Python 3.8 or higher
- SQL
- Pandas
- Numpy
- Matplotlib, Seaborn
- Plotly Dash
- Beautiful soup
- Folium
## Full project report here[]()
