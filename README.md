# Influenza-Season
Predictive analysis on influenza trends to advise of medical staffing needs for the upcoming influenza season.
# Key Questions
    ● Who is effected by influenza? 

    ● When is flu season?

    ● Where are influenza death rates the highest?

    ● What are the top 5 states with the most flu deaths?  
    
    ● Is there a significant difference in the deaths of the vulnerable population compared to the rest of the population? 
    
# Tools Used in the Project
1. Excel
2. Tableau for Dashboard and Story
# Data
Main Dataset along with data dictionaries can be found at: https://data.chhs.ca.gov/dataset/hospital-encounters-for-homeless-patients. 

Time Series Dataset can be found at: https://datahub.io/gavram/homelessness#readme. 
# Limitations
It is important to keep in mind these are the numbers of encounters and should not be construde for population numbers.  As one person may only have 1 hospital encounter, and another person may have 5+ visits.   

# Findings: 
  #### County Demographics
Southern California, Los Angeles in particular, and the San Francisco Bay area are hit the hardest with the most hospital encounters.  
#### Hospital Demographics
Los Angeles has the highest number of encounters and they also have the highest number of shortages for primary care and mental health.  Los Angeles had 13 facilities that were in shortage area. 

There were many more homeless encounters in the ER compared to Inaptient Hospitalizations. 
#### Patient Demographics
Age Group 40-59 had the highest number of instances.  After doing linear regression there was a significant correlation between the Age Group 40-59 and total encounters from the other age groups.  

The white/caucasian race has the most encounters. While Native American/Alaskan Native had the fewest. 

70% of the encounters were males, while 30% of the encounters were females. 

#### Cluster Analysis
Cluster Analysis was performed to look for more relationships; however, due to the limited continuous data I was not able to get any additional insight. 

#### Time Series Analysis
This was performed on the homeless population in the USA from 2017 - 2018.  Beacause this dataset was not broken down by state, I could not extract information for California.  This was a standalone dataset simply for the time series analysis.  

During the time series analysis, the data provided was non-stationary.  This was confirmed through Autocorrelation testing and the Dickey Fuller Test.  In order to proceed with Time Series Analysis, I stationariezed the data.  Once the data was then stationary, I was able to see that homeless rates were on the rise from 2003 - 2018. 
# Recommendations: 
- Focus on Southern California (especially LA county) and the San Francisco Bay area as they have the greatest numbers of incidents.  This includes increasing primary care and mental health staffing. 


- Begin tracking overarching themes of what brings the patient to the hospital in order to find out if there are any trends where age-appropriate resources can be provided. 

- Further explore why males have more encounters than females.


- Discuss how hospitals can be more proactive about healthcare needs for homeless patients, as this may help to reduce the amount of ER visits. 


- Extra Thought:  Ensure that staff, administrators, and clinicians are physically, mentally, and emotionally trained to handle difficult homeless patient encounters.  This will help staff to feel equipped to handle the situations if they arise, and thus providing a better staff and patient experience. 








