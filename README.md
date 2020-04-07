# KBS Group 9 - Project

## Team Members:
- Aditya Kamble (akamble@uncc.edu)
- Sidharth Panda (spanda3@uncc.edu)


### 1. Research Questions
  - What is the number of accidents of a state as compared to its adjacent states?
  - Why and how wind speed and wind direction contribute to accidents?
  - How does Weather condition and time affect visibility which results in the number of accidents?
  - Do accidents happen due to stop signs w.r.t time of the day?
  - Is the accident rates in different states higher due to different Weather Condition?
  

### 2. Domain and Data: Identify domain and source(s) of data
#### Dataset - US Accidents (3 Million Records)

**A Countrywide Traffic Accident Dataset (2016 - 2019)**

This is a countrywide traffic accident dataset, which covers 49 states of the United States. The data is collected from February 2016 to December 2019, using several data providers, including two APIs which provide streaming traffic event data. These APIs broadcast traffic events captured by a variety of entities, such as the US and state departments of transportation, law enforcement agencies, traffic cameras, and traffic sensors within the road-networks. Currently, there are about 3.0 million accident records in this dataset.

Since the dataset contains 3.0 million records, It’s difficult for a user to bring out the useful insights.
Specific questions like the Total number of accidents per city or state can be calculated using statistics, but more details related to the individual factors affecting the result can be sought by visualization.  Having a multiple columns helps in finding the relation between several factors responsible for the accidents can be explored and explained through visualization.
![image](US_Accidents_Report-UserDashboard.JPG)

**Kaggle Dataset Link:** https://www.kaggle.com/sobhanmoosavi/us-accidents

- Preprocessing:
  - Check for Missing values and replace them using Mean or Median of data
  - Work on feature selection among given features and generate new features using grouping and aggregation techniques
  - Prepare dataset features to be compatible with different types of visualization
  
- Size of Dataset - 3 Million records with 49 feature columns

- Tentative plan for analysis on GCP
  - EDA and Preprocessing - 03-23-2020
  - Dashboard for User group, Dashboard for Data Engineers - 03-26-2020
  - GCP further processing - ML -03-29-2020
  - Evaluation of results - 04-01-2020
  - Steps for production model - 04-07-2020
  - Final Dashboard for User Group - 04-15-2020

(note:  analysis must use Hadoop, Big Query, PySpark, as many tools as possible from class)

- Research citations:  (three scholarly papers that assist with your project in terms of domain, processing, preparing data, etc.) – provide citations and one paragraph abstract
  - https://crashstats.nhtsa.dot.gov/Api/Public/ViewPublication/811059
