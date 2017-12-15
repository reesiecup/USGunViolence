# USGunViolence
This is a project using Python to explore the pattern of mass shootings happened in the past 50 years in the US. I downloaded the data from Kaggle, started with descriptive statistics and graphs, and ran a couple of regression models that may help answer the questions. The Python libraries used in this project included panda, numpy, matplotlib, seaborn, datetime, statsmodels, and basemap. This is an ongoing project. An updated Jupyter notebook file will be uploaded once I made progress.

# The Data
The data was downloaded from here: https://www.kaggle.com/zusmani/us-mass-shootings-last-50-years
The contributors had compiled 5 versions of the data as of Nov, 5th, 2017. This project used the 5th version because it contained the most variables comparing to other versions. 

# Questions Asked
1. How many shootings are there each year from 1966 to 2017?
2. Does the number of shootings vary across months and weekdays?
3. What can the data tell us about the shooters? The race, age, gender, and cause of the shootings.
4. Does the shootings categorized in psychotic motive really have a shooter with mental disorder?
5. Does the location determine the number of victims?
6. Does the location have anything to do with the scenario where the number of the injured were more than the dead?
7. Does the cause have anything to do with the number of the victims?
8. Can we predict the number of the victims for each year?
9. When and where are these shootings located?

# Next Step
1. Aggregate the current data in the unit of state and combine it with additional information, such as each state's firearm regulation, gun-owned rate, political orientation. 
2. Run a correlation between the amount of gun lobby money and the number of mass shootings across the past 50 years.

# Limitation
The number of mass shootings included in this data set is less than the record presented on Mass Shottings Tracker (http://www.shootingtracker.com/), however, this data does provide more information regarding each incident and thus it is more suitable for answering some of the questions above. When it comes to the question directly regarding the number of shootings, the results may be slightly different based on which data set is used.
