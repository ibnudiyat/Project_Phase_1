OVERVIEW

One of the means of the transport is by air.   In United States , it experience number of accidents in aviation sector every year.  Safety of aircrafts, pilot and other users is paramount.  We will figure out the causes and factors that contribute these accidents

Business problem 

Considering the number of accidents in aviation sector notwithstanding the modern aircraft  in United States is an alarming. Hence is necessary to find out the causes and make recommendation for future safety improvement. 

Data

The data set used for this analysis was downloaded from Kaggle website.  The NTSB database recorded the accidents and incidents from 1942 to 2023. 
link : https://www.kaggle.com/datasets/khsamaha/aviation-accident-database-synopses/data

Questions 
What is the trend of the accidents for the last years?

Which are the state that the accidents occurs mostly in United States?

Which aircrafts are associated with accident mostly?

How to improve the safety of aviation sector?

Description of Data

#Importing the necessary libraries

import pandas as pd #Pandas Library

import numpy as np #Numpy Library

import matplotlib.pyplot as plt #Matplotlib library

import seaborn as sns #Seaborn library

Loading the Data

#Reading our dataset in csv file and name variable df(Dataframe)
df = pd.read_csv('AviationData.csv', encoding= 'latin-1')

Cleaning the Data

Clean df (Dataframe)

Clean df_State (Dataframe)

Merge df and df_State


Visualizations

<<<<<<< 
=======
![image](https://github.com/user-attachments/assets/d441d5ae-8574-4f8c-b005-21f849e87c1c)

![image](https://github.com/user-attachments/assets/5b01101d-b2bd-489b-a71d-44f02d6dea06)

![image](https://github.com/user-attachments/assets/3d019868-1fb5-4471-aee7-ffc5dd979d9a)

Findings

California, Texas ,Florida and Alaska have the highest number of accidents.

Cessna Aircraft are mostly involved an accident. Piper and Beech aircrafts also have significant scenarios of accidents.

The accidents has declined from 1987 to 2022

Tableau Link
https://public.tableau.com/app/profile/abdirahman.farah/viz/AVIATIONACCIDENTSANALYSISINUS/AVIATIONACCIDENTSANALYSISINUS?publish=yes



