# Bikes Dataset Exploration
## by Michael Mwangi Ndirangu


## Dataset

> The dataset used for analysis is the Ford GoBike System Data: This data set includes information about individual rides made in a bike-sharing system covering the greater San Francisco Bay area. The dataset contains information with regards to 183,412 observations with regards to 16 variables related to the bike share. Variables include; Bike duration in seconds, member_birth_year, member_gender, user type, and whether the bike share was used for the duration of the whole trip. The dataset can be found in udacity repository here; https://video.udacity-data.com/topher/2020/October/5f91cf38_201902-fordgobike-tripdata/201902-fordgobike-tripdata.csv

>Age variable was generated based on the birth_year column. The data was then wrangled to remove null values in the age column and also rows with other gender were removed to allow for comparison among males and females only


## Summary of Findings
>For duration in seconds, the distribution is highly skewed to the right as there is a long tail to the right. This indicates that there are a few individuals whose bike utilization is much longer than that of the majority. No unsuual points as all points are within 24 hours.

>The relationship between age and duration in seconds was investigated by using a scatterplot and heat map. Analysis showed that there is a somewhat negative relationship between age and duration. The duration of younger people is somewhat higher for younger geneartion and decreases with increase with age.Relationships between duration and the variables; user_type, gender, and bike_share_for_all_trip were also investigated. This was done by use of violinplot,boxplot, and point plot. Based on the plots, there did not appear to be any clear differences between duration by gender and bike_share_for_all_trip. However, there were clear differences in duration based on user_type. Customers generally have higher durations than subscribers.

> Initial bivariate analysis showed that gender does not impact on duration in seconds. However, by adding the age variable, then gender becomes a predictor of duration in seconds. For individuals aged below 80, then females have higher durations than males. However, for individuls aged above 80, then males generally have higher duration than females.> In terms of the relationship between duration and bike_share_for_all_trip,bivariate analysis showed no clear relationship. The relationship remains the same even when the age variable is included. The difference in duration overlaps between the different ages and no general differences in duration can be observed. In terms of user type, the relationship remains the same regardless of age, gender or bike_share_for_all_trip. The relationship is that regardless of the added variables, customers generally have higher duration than subscribers. In other words, regardless of age, gender,or whether the bike share is for the whole trip, a customer will generally have a higher duration than a subscriber. 

>Outside of the main variables of interest, Analysis was done to evaluate whether any significant relationship exists between user_type and gender. Analysis showed that user_type is not dependt on gender as there are similar proportions of customers and subscribers for both males and females

## Key Insights for Presentation

> For the presentation I focused on the distribution of the main vaeriable of interest, duration. I also focused on the relationship of duration with the variables of interest; gender,age,user_type, and bike_share_for all trips. The reason for highlighting all is that it shows the variation of the relationship between the variables and duration. For bike_share_for_all_trip, there was no significant relationship; for gender, the relationship only existed after age variable was addded; and for user_type a clear relationship is present regardless of the other variables. 
