# Individual-Project---First-Version


# Individual Project
#### By Prachi Sharma

### Datasets Used

1. Speed Camera Violations

2. Red Light Violations

3. Traffic Crashes Violations

Dataset Reference - 

https://data.cityofchicago.org/Transportation/Speed-Camera-Violations/hhkd-xvj4

https://data.cityofchicago.org/Transportation/Red-Light-Camera-Violations/spqx-js37

https://data.cityofchicago.org/Transportation/Traffic-Crashes-Crashes/85ca-t3if

## Data Analysis of Speed Camera Violations & Red Light Camera Violations

#### The Datasets are joined on the basis of Zipcodes, Wards & Date of Respective violations to extract the related violations specific to Time & Venue. 

**The Dashboard is published at the below link- **

https://public.tableau.com/profile/prachisharma#!/vizhome/IP_Version1-SpeedCamRedLightViolationsAnalysis/TopZipCodesRedLightSpeedCamViolations_1?publish=yes

### Data Insight 1

The Top 10  & Bottom 10 Zipcodes with highest and lowest Red Light Violations are extracted to identify the red Zone areas in Chicago. The mayor of Chicago would be interested in knowing these areas so as to focus on their regulations to control these violations. 

When we bring Speed Violations into picture we see that the speed violations in these areas is **also very significant** leading to the fact that strict regulations are required in these zones.

**Visualization -- <a href='https://github.com/Psharma2193/Individual-Project---First-Version/blob/master/DI_1.PNG' rel='nofollow'>Data Insight 1</a> **


### Data Insight 2

To analyze deeper I used scatter plot to understand how much Speed Camera Violations are affected by Red Light Camera Violations. On plotting a scatter plot, their relationship seems to give a positive correlation. 

**Visualization -- <a href='https://github.com/Psharma2193/Individual-Project---First-Version/blob/master/DI_2-Scatter%20Plot.PNG' rel='nofollow'>Data Insight 2</a>** 

Scatter Plot++ zooms into the concentrated area of the first scatter plot

### Data Insight 3

This visualization Presents the existing trend of violations and forecasted violations in coming years. It is interesting to note that as the Red light Violations increase so does the speed camera violations. It clearly shows the close relationship between their trend. Also, for month analysis we see that for every year the violations hit the peak during the mid of the year and gradually decrease during the end and start of next year.

This same pattern is visible in the forecasted trend. This gives a cue to authorities to strengthen regulations during these times.

**Visualization -- <a href='https://github.com/Psharma2193/Individual-Project---First-Version/blob/master/DI_3%20-%20Forecast.PNG' rel='nofollow'>Data Insight 3</a>** 

## Data Analysis of Speed Camera Violations & Traffic Crashes

#### The Datasets are joined on the basis of Addresses to extract the related violations and crashes specific to a Venue. 

**The Dashboard is published at the below link- **

https://public.tableau.com/profile/prachisharma#!/vizhome/IP_Version1-SpeedCamCrashInjuriesAnalysis/Top5CameraIDwithhighestCrashInjuriesAnalysis?publish=yes

### Data Insight 4

First, I've tried to explore the dataset. Using the total injuries, I identified top Camera IDs that reported maximum no of crashes. Then I brought the speed violations for these Camera IDs and they seem to have followed the similar peaks. On analyzing deeper the speed violations limit for all these camera Id's was 30.
Looking at the Weekday analysis for violations, it came across that the majority of crash injuries reported in children safe zone on Friday and Saturday whereas Weekdays rank highest for Speed camera Violations. Surprisingly, on Thursday there are hardly any violations or crashes reported in the dataset. On analyzing deeper the speed violations reported for all these  

Crashes are serious case of negligence and them happening in the Childen safe zone is a matter of great concern that should be addressed with required actions from authorities. 

**Data Exploration Image -- <a href='https://github.com/Psharma2193/Individual-Project---First-Version/blob/master/DI_4-DEX.PNG' rel='nofollow'>Data Exploration</a>** 

**Visualization -- <a href='https://github.com/Psharma2193/Individual-Project---First-Version/blob/master/DI_4.PNG' rel='nofollow'>Data Insight 4</a>** 


### Conclusion
Chicago is widely known for its high crime rate. Handling speed & traffic violations can become secondary for authorities. After looking at the data the authorities can identify the areas that need strict law enforcement like regular police patrolling and ticketing policy. The dataset is from 2014 - 2019 and it clearly speaks that installation of Speed camera in 2014 has led to decline in violation cases over the years. The citizen may have become conscious of their actions as they are at higher risk of getting caught by authorities. This is in a way encouraging and positive signal for authorities to increase cameras in children safety zone to furthermore decrease violations. 
