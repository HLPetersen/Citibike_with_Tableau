# Citibike with Tableau #
## Overview of Analysis ##
This analysis is based on August 2019 data for Citi bike in New York City.  The analysis provides an overview of the data from a csv file from https://citibikenyc.com/system-data. The August 2019 csv contains information on over 1,000,000 bike trips. For each trip, there is ride ID, ride type, starting time, ending time, start station name, start staion ID, end station name, end station ID, starting longitude and latitude, ending longitude and latitude, whether the person is a suscriber, trip duration, bike ID, and birth year of the user. 

## Purpose of Analysis ##
The purpose of this analysis is to show investors how the bike-sharing program works in NYC and how it could be a solid business model for Des Moines, Iowa as well. It is meant to provide an overview of a busy month in New York City for investors to get an idea of how the business could translate to the new area.

## Results ##

### Ride Peak Times ###

<img width="677" alt="hours by user" src="https://user-images.githubusercontent.com/116980760/227745047-9b686a7d-b566-4360-ac33-d344529f2310.PNG">
Ride peak start times seem to correspond with typical "work hours". 7am and 5pm both seem to have increased demand. 

### Heatmap of Busiest Hours ###

<img width="300" alt="peaktimes" src="https://user-images.githubusercontent.com/116980760/227745094-a21cb74e-b331-4956-983a-4f821a4b59b7.PNG">
The heatmap shows that stoptimes are busiest at those "work hours". Most stoptimes fall on weekdays at 7am to 9am and 5pm to 6pm. 

### Heatmap of Busiest Hours by Gender ###

<img width="465" alt="gender stoptime" src="https://user-images.githubusercontent.com/116980760/227745120-15bc8fb5-d3d1-4394-9259-0b1645c94581.PNG">
Busiest hours seem to follow the same pattern regardless of gender. 

### Breakdown of Users by Gender ###
<img width="500" alt="gender breakdown" src="https://user-images.githubusercontent.com/116980760/227745026-9005720f-b47c-460a-bd0f-042380d4beec.PNG">
The majority of citibike users in NYC are male. 

### Ride Duration ###
<img width="668" alt="trip duration" src="https://user-images.githubusercontent.com/116980760/227745088-24cc9d3c-0019-4fd2-b644-133946da2cdc.PNG">
Ride duration typically is less than 60 minutes which seems to conform to the conclusion of users mostly using the bikes for work commute.

### Ride Duration by Gender
<img width="661" alt="trip duration by gender" src="https://user-images.githubusercontent.com/116980760/227745077-b9068bb4-1cdb-4f95-b11e-0c72011ce05e.PNG">
Ride duration seems to follow the same pattern regardless of gender.

### Heatmap of Use by Gender and User Type ###
<img width="300" alt="usertype" src="https://user-images.githubusercontent.com/116980760/227745129-aa2e81e3-87b7-411e-aab2-dd3fbeefb98a.PNG">
Citibike subscribers seem to use the service much more than others. 

## Summary ##
- Riders seem to be using the service for work commute.
- The gender of user does not seem to influence use hours nor ride duration.
- Making subscriptions a priority might help increase trips as they use the service more.
- Two additional visualizations that would help in uderstanding demographic use would be a heatmap of users peak day usage bye age and a bar graph of peak hour useage by age. 
    
    
  
  [Link to Tableau Story](https://public.tableau.com/app/profile/heidi.petersen/viz/Citibike_16797145517690/Story1?publish=yes "Link to Tableau Story")
