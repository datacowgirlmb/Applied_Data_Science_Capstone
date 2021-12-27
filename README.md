# Coursera's Applied Data Science Capstone Project

## *Week 1*
### Data Collection via API
Notebook: [SpaceX_Data_Collection.ipynb](https://github.com/datacowgirlmb/Applied_Data_Science_Capstone/blob/master/SpaceX_Data_Collection.ipynb)<br>
Capture data using the SpaceX API.<br>
<br>
### Data Collection via Webscraping
Notebook: [SpaceX_Data_Collection_Webscraping.ipynb](https://github.com/datacowgirlmb/Applied_Data_Science_Capstone/blob/master/SpaceX_Data_Collection_WebScraping.ipynb)<br>
Capture additional data by webscaping the "List of Falcon 9 & Falcon Heavy Launches" Wikipedia page.<br>
<br>
### Data Wrangling
Notebook: [EDA.ipynb](https://github.com/datacowgirlmb/Applied_Data_Science_Capstone/blob/master/EDA.ipynb)<br>
- Account for NULL values
- Calculate the number of occurences of each type of orbit
- Calculate the number of mission outcomes per orbit type
- One-hot encode the Outcome column

## *Week 2*
### Exploratory Data Analysis with SQL
Notebook: [EDA_with_SQL.ipynb](https://github.com/datacowgirlmb/Applied_Data_Science_Capstone/blob/master/EDA_with_SQL.ipynb)<br>
Import data into a DB2 instance, & review data by querying.

### Exploratory Data Analysis with Pandas & Matplotlib
Notebook: [EDA_with_DataVisualization.ipynb](https://github.com/datacowgirlmb/Applied_Data_Science_Capstone/blob/master/EDA_with_DataVisualization.ipynb)<br>
- Visualize the relationships:
  - Flight Number vs. Launch Site
  - Payload vs. Launch Site
  - Success of each orbit type
  - Flight Number vs. Orbit Type
  - Payload vs. Orbit Type
  - Launch success yearly trend
 - One-hot encode categorical columns Orbit, LaunchSite, LandingPad, & Serial

## *Week 3*
### Interactive Visual Analytics with Maps
Notebook: [Interactive_Visual_Analytics_with_Folium.ipynb](https://github.com/datacowgirlmb/Applied_Data_Science_Capstone/blob/master/Interactive_Visual_Analytics_with_Folium.ipynb)<br>
Use Folium to create maps of the launches.
- Mark all launch sites
- Mark success/failure of launches at each site
- Calculate the distances between launch site & locations in proximity

### Interactive Dashboard
Notebook: [spacex_dash_app.py](https://github.com/datacowgirlmb/Applied_Data_Science_Capstone/blob/master/spacex_dash_app.py)<br>
Use plotly to create an interactive dashboard with various charts. Create:
- A drop-down menu of the various launch sites
- A pie chart displaying the total number of successful launches for the selected site
- A scatter plot displaying the correlation between payload size & launch success

## *Week 4*
### Predictive Analysis
Notebook: [ML_Prediction.ipynb](https://github.com/datacowgirlmb/Applied_Data_Science_Capstone/blob/master/ML_Prediction.ipynb)<br>
Standardize the data & assign training & test sets. Perform predictive analysis using logistic regression, Support Vector Machine, decision trees, & K Nearest Neighbors.
