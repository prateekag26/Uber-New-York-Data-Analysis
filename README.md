# Uber New York Data Analysis using Python



## Introduction
This repository contains the Uber New York Data Analysis project. The project aims to analyze Uber pickup data in New York City to uncover patterns in ride demand, peak hours, and popular locations using various data analysis techniques in Python. The analysis provides valuable insights into urban mobility trends, which can inform business decision-making and enhance understanding of travel behavior in a bustling metropolis like NYC.


## Table of Contents

- Installation
- Dataset
- Technologies Used
- Results and Insights
- Learnings 
- Deployment
- Conclusion


## Installation

To run this project follow following steps:

#### 1. Clone the repository:

```bash
https://github.com/CoderAdi003/Uber-New-York-Data-Analysis

cd uber-nyc-data-analysis

```


#### 2. Set up a virtual environment (optional but recommended):

```bash
python3 -m venv env
source env/bin/activate  # On Windows: env\Scripts\activate

```

#### 3. Install the required Python libraries:

```bash
pip install pandas as pd 
pip install numpy as np
pip install matplotlib

# For Seaborn and plotly
pip install seaborn 
import seaborn as sns
pip install plotly-geo==1.0.0 

# For geopandas
pip install geopandas 
conda install --channel conda-forge geopandas
!conda install geopandas

 # Folium
pip install folium 


``` 
## Technology Used

- **Programming Language:** Python
- **Libraries:**  Pandas, NumPy, Matplotlib, Seaborn, Plotly, Folium, Geopandas
- **Environment:** Jupyter Notebook
- **Visualization Tools:** Matplotlib, Seaborn, Plotly for interactive visualizations




## Results and Insights

- ### Time-Based Analysis
    Identifying peak hours of the day and busiest days of the week and analyzing monthly and seasonal variations in ride volume.
- ### Geospatial Analysis
    Visualizing popular pickup locations using heatmaps and identifying ride density and hotspots across different regions of New York City.
- ### Top Pickup Locations
   Manhattan accounts for nearly 70% of all pickups, with key hotspots like Times Square, Financial District, and Midtown.

- ### Peak Hours of Demand
     The highest ride requests occur during 8:00 AM - 9:00 AM and 5:00 PM - 6:00 PM, correlating with morning and evening rush hours. An average of 15,000 pickups per hour during these peak times.

- ### Seasonal Impact
     Rides increase by about 15% during warmer months (April-October) compared to colder months (November - March).

- ### Monthly Trends
  The busiest month recorded is September, with over 450,000 pickups. The slowest month is January, with approximately 320,000 pickups.

- ### Temporal Patterns
   Late nights (1:00 AM to 3:00 AM) on weekends, especially Saturdays, experience increased demand, with about 20,000 pickups during these hours, concentrated in entertainment districts. Weekdays are more consistent with steady demand through the day, peaking around commuting hours.
## Lessons and Learnings

### 1. Data Cleaning and Preprocessing
- #### Handling Missing Data
   Learned how to manage missing values effectively using techniques such as filtering, imputing, or removing incomplete rows.

- #### Date and Time Formatting
  A significant part of the project involved converting raw timestamps into usable formats, like extracting hour, day of the week, and month from datetime objects to analyze temporal patterns.

- #### Data Filtering
  Filtered the data to focus on specific time frames or geographic regions, which improved the relevance of your analysis.

 ### 2. Exploratory Data Analysis (EDA)
 EDA techniques helped you identify trends in ride demand based on time of day, days of the week, and geographic locations.

### 3. Data Visualisation
 Creating insightful visualizations that effectively communicate data trends and insights.


## Deployment
To deploy this project:

 1. Install Jupyter Notebook (Please watch any tutorial on youtube, its easy to install).

```bash
 jupyter notebook UberDataAnalysis (1).ipynb

```
2. Run the above file in Command Prompt.

## Conclusion

The Uber New York Data Analysis project provided valuable insights into ride patterns, peak demand periods, and operational efficiencies. The findings can be used to optimize driver allocation, improve customer satisfaction, and enhance surge pricing strategies.


## Authors

- [@CoderAdi003](https://github.com/CoderAdi003)


## Feedback

Feel free folks to drop any feedbacks you have at adityakumar100aditya@gmail.com


## 🔗 Links
[![linkedin](https://img.shields.io/badge/linkedin-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/aditya-kumar-b08404226/)


