# (Gorkha 2015 Earthquake Dataset Exploration)
## by (Sekinat Oyero)


## Dataset
This dataset contains the household survey of the 7.8Mw earthquake that happened in Gorkha region in April, 2015. It gives information about the 260601 building structures and damage in the earthquake affected region. each row represent a building and each column represent a property and there are 39 columns. The dataset can be found here (https://www.kaggle.com/datasets/mullerismail/richters-predictor-modeling-earthquake-damage). The dataset came as a train and test csv files.I performed data cleaning on the data by merging the two csv files together. Also, the data has tidyness issues because it contains columns that should have been under just a column. I also mapped the target variable to a proper descriptive one. At the end of the wrangling process, the data columns has reduced to 21. Only a few of these columns were used in the analysis  



## Summary of Findings

In the exploration phase, I found a correlation between age of houses, count of floor before earthquake and damage grade.High rise older houses shows increase in dammage grade with height. Also the predominant foundation type is r-type foundation and it is more susceptible to high grade earthquake damage. The r and u type foundation worsen with age and also with the number of floors. Land surface condition is majorly t-type and it shows no variation with fundation type, age, and damage grade. Newer houses with one and two floors have almost equal proportion of damage grade which shows there are other features at play. The reason was apparently because of the building material. Mud mortar stone  and timber houses are highly susceptible to damage. Mud mortar stone  and timber houses which are majorly houses with no use and low number of floor are severely damaged. Also  those with use specifically agriculture and rental are damaged greatly which is also apparently due to the nature of building material - mud mortar stone, mud mortar brick and timber
Lastly, Medium - High grade damage in houses with secondary use increased around the same age range of those without a secondary use just that age is also a major determinant. Therefore a much older houses suffer both medium and high destruction. Houses with with seconday use are prone to all kinds of damage. These findings came about using differnt visualization plots and they are; clustered barcharts, barcharts, histplots, boxplots and violin plot

Major transformation made were plotting log of age because there were instance of a few very old houses. At other times, limits were set on some axes in order to zoom into a particular value.  
