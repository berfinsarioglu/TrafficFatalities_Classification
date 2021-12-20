# Project-03:  Classifying Traffic Fatalities

This repo contains Project-03 data and solution at Istanbul Data Science Academy. Project-03 is about Classification of Traffic Fatalities Dataset.

## Classification:

Classification in machine learning and statistics is a supervised learning approach in which the computer program learns from the data given to it and make new observations or classifications.

Classification is a process of categorizing a given set of data into classes, It can be performed on both structured or unstructured data. The process starts with predicting the class of given data points. The classes are often referred to as target, label or categories.

The classification predictive modelling is the task of approximating the mapping function from input variables to discrete output variables. The main goal is to identify which class/category the new data will fall into. (Edureka)

## Objective and Goal:

Classifying traffic accidents according to daytime and nighttime

* CSV to PostgreSQL
* Join Tables
* Connect PostgreSQL to Pandas
* Exploratory Data Analysis
* Feature Engineering
* Applying Algorithms


## Data:
Data obtained from Kaggle
https://www.kaggle.com/nhtsa/2015-traffic-fatalities
https://crashstats.nhtsa.dot.gov/Api/Public/ViewPublication/812315

## Information of Some Features

* st_case 	:  Case id
* fatals	: Total number of fatals in a unique case (sum)
* drunk_dr	: 0:not drunk 1:drunk 
* persons	: Total number of persons in a unique case (sum)
* state         : USA States
* weather	: {No Additional Atmospheric Conditions, 'Clear', 'Rain',  'Sleet, Hail’,  'Snow’, 'Fog, Smog, Smoke', 6: 'Severe Crosswinds’,  'Blowing Sand, Soil, Dirt’,  'Other', 'Cloudy', 11: 'Blowing Snow’,  'Freezing Rain or Drizzle’,  'Not Reported', 'Unknown’}
* ve_total	: All of the vehicles in  the crash. (in-transport and not in-transport) (sum)
* doa           : Total number of dies at scene  (sum)
* mod_year 	: 1929 – 2006 (mean)
* crashTime	: Datetime64
* mdrmanav	: The things this driver attempted to avoid (max)

	{'Driver Did Not Maneuver To Avoid’, 'Object’, 'Poor Road Conditions’, 'Live Animal', 'Motor Vehicle’,  'Pedestrian, Pedalcyclist or Other Non-Motorist’,  'Phantom/Non-Contact Motor Vehicle’, 'No Driver Present/Unknown if Driver Present’,  'Not Reported’,  'Unknown’}


* mdrdstrd 	: Distractions (max)

 	{ 'Not Distracted', 'Looked But Did Not See’,  'By Other Occupant(s)', 'By a Moving Object in Vehicle’, 
'While Talking or Listening to Cellular Phone’,  'While Manipulating Cellular Phone’,  'While Adjusting Audio or Climate Controls’,
'While Using Other Component/Controls Integral to Vehicle’,  'While Using or Reaching For Device/Object Brought Into Vehicle', 
'Distracted by Outside Person, Object or Event', 'Eating or Drinking', 'Smoking Related', 'Other Cellular Phone Related', 
'No Driver Present/Unknown if Driver Present', 'Distraction/Inattention', 'Distraction/Careless', 'Careless/Inattentive', 
'Distraction (Distracted), Details Unknown', 'Inattention (Inattentive), Details Unknown', 'Not Reported', 'Lost In Thought/Day Dreaming', 
'Other Distraction', 'Unknown if Distracted'}  

           

