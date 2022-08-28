# [Applied Data Science Capstone](https://github.com/aaysul/applied-data-science-capstone)

This repository holds the notebooks that were completed during the Capstone Project for the IBM Data Science Professional Certificate on Coursera. The aim is to predict whether the SpaceX Falcon 9 first stage will land based on the data from previous launches. The data supporting the prediction is gathered using various sources. The project involves various steps to gather, clean and analyze data and then prepare a presentation to share the findings. The following is the step by step breakdown of the project.

  1. Data Collection
  2. Data Wrangling 
  3. Exploratory Data Analysis (EDA) using SQL
  4. Exploratory Data Analysis (EDA) using Pandas and Matplotlib
  5. Interactive Visual Analytics using Dashboards
  6. Predictive Analysis (Classification)
  7. Final Presentation
  
## 1. Data Collection  
   The data collection process involves using different methods to acquire data. These include using API or web scraping.
   * **Using SpaceX API** \
  This is the first lab for the data collection process. It involves data collection on SpaceX launches using the API. The notebook for the lab is available [here](https://github.com/aaysul/applied-data-science-capstone/blob/main/spacex-data-collection-api.ipynb). The data through API is available as follows,
      - Booster version details are available at https://api.spacexdata.com/v4/rockets/
      - Launch Site details are at https://api.spacexdata.com/v4/launchpads/
      - Payload data is available at https://api.spacexdata.com/v4/payloads/
      - Cores data is at https://api.spacexdata.com/v4/cores/
   * **Using Web Scraping** \
   This is the second lab for the data collection process. It involves data collection through web scraping. The notebook for this lab is available [here](https://github.com/aaysul/applied-data-science-capstone/blob/main/spacex-data-collection-webscraping.ipynb). The data is available as follows,
      - SpaceX Falcon9 and Falcon Heavy launch data available at https://en.wikipedia.org/wiki/List_of_Falcon_9_and_Falcon_Heavy_launches
## 2. Data Wrangling
   The purpose of this lab was to perform exploratory data analysis (EDA) to find patterns in data and determining the training labels for supervised learning model. The notebook for this lab is [here](https://github.com/aaysul/applied-data-science-capstone/blob/main/spacex-data-wrangling.ipynb). Following tasks are performed,
   * Explore number of Launches per Launch Site
   * Explore number of Launches per Orbit
   * CreateLanding Outcomes Labels for Training
   
The landing outcomes were converted to landing class.

| **Outcome**       | **Class**   |
| ------------------|------------:|
| Successful        | 1           |
| Failure           | 0           |
        
## 3. Exploratory Data Analysis (EDA) using SQL
   This lab involves using SQL within the python environment as the primary language for manipulation. The lab notebook is [here](https://github.com/aaysul/applied-data-science-capstone/blob/main/spacex-eda-sql-coursera_sqllite.ipynb). The following launch information is explored,
   * Landing Outcomes by Launch Sites
   * Landing Outcomes by Landing Platforms
   * Landing Outcomes by Dates
   * Payload Mass by Booster Versions
   * Ranking of Landing Outcomes within given period
   
   
   
   
   
   
   
   
   
