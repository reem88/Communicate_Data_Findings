# Ford GoBike Dataset Exploration
## by Reem Helal


## Dataset

> Ford GoBike data set includes information about individual rides made in a bike-sharing system covering the greater San Francisco Bay area.

> Data Source : https://www.lyft.com/bikes/bay-wheels/system-data

The data set features are :

    Trip Duration (seconds).
    Start Time and Date.
    End Time and Date.
    Start Station ID.
    Start Station Name.
    Start Station Latitude.
    Start Station Longitude.
    End Station ID.
    End Station Name.
    End Station Latitude.
    End Station Longitude.
    Bike ID.
    User Type (Subscriber or Customer – “Subscriber” = Member or “Customer” = Casual).

> This document will include the EDA of the year 2017. 


## Summary of Findings

> As a conclusion, we can say that Autumn was the most active bike riding season where Summer comes to the fist place when we put the duration of the trip in our consideration. The thing which is really strange that there is NO bike riders in Spring, and I think that is because there is no data for Spring season in this dataset. Subscriber users are the most bike riders in all season where Customer users comes to the first place when it comes to consider the duration of the trip. Moreover 8 Am and 5 PM are the most biking trips across the working days for all seasons.



## Key Insights for Presentation

> The keys of interests are : 
> 1. The duration of the bike trip.
> 2. The seasons of bike trips.
> 3. The stations where the bike trip starts and ends.
> 4. The time details of the bike trip in 2017 (month, day and hour).
> 5. Bike riders types.

> We delete useless features from the dataset which are : (1. Start Station Latitude. 2.Start Station Longitude. 3.End Station Latitude. 4. End Station Longitude)from the dataset. Moreover, we change the datatype of Star-Time and End-Time to datetime and extract time details from it (month, day, hour), using these extra information we build a season fields in the dataset.