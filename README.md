# Ford GoBike System Dateset
## by Mohamed Ahmed


## Dataset

> This project is divided into two major parts. In the first part, you will conduct an exploratory data analysis on a dataset Ford GoBike System Data. I will use Python data science and data visualization libraries to explore the dataset’s variables and understand the data’s structure, oddities, patterns and relationships. The analysis in this part should be structured, going from simple univariate relationships up through multivariate relationships. 


> In the second part, I will take my main findings from my exploration and convey them to others through an explanatory analysis. To this end, I will create a slide deck that leverages polished, explanatory visualizations to communicate my results.

> This document explores a dataset containing the trip data of the ford gobike approximately 183,412 with 16 features (duration_sec, start_time, end_time, start_station_id, start_station_name, start_station_latitude, start_station_longitude, end_station_id, end_station_name, end_station_latitude ,end_station_longitude, bike_id, user_type, member_birth_year, member_gender, bike_share_for_all_trip). Most variables are 9 numerical, and others are 2 datetime, 4 object type and 1 is boolean type.

> Project Details:

Dataset : https://www.fordgobike.com/system-data
Exploring Data
Document the Story
Communicating the Story
Main Findings from the Analysis:

> This bike share system has greatly identified the need of the times and created a business that is profitable to both the end customers and the business. It is definitely a win-win solution.

> Between the User types, Customers and Subscribers the highest usage in terms of duration was by Customers in the year 2019
> Majority of the system’s bookings came through their app bookings – Lyft
> The station that received the highest demand in the year 2019 was the station 58 which as the Market St at 10th Street. However, after cleaning the data and removing all the bookings that were made through non-traditional booking methods which is app and dipper, the station with the highest demand was the station 296, which is 5th St at Virginia Street.
The User type who used this station the most were the Subscribers



## Summary of Findings

   <li><strong>User Type</strong></li>
       <ul>
           <li><strong>subscribers are:</strong></li>
               <ul>
                   <li>more likey to travel from 500 to 1500m</li>
                   <li>more likey to be between 20 - 30 year old</li>
                   <li>more likey travel a duration of 0 to 500s</li>
               </ul>
           <li><strong>customers are:</strong></li>
                <ul>
                   <li>more likey to travel from 1000 to 2000m</li>
                   <li>more likey to be between 20 - 30 year old</li>
                   <li>more likey to travel a duration of 500 to 1000s</li>
               </ul>
       </ul>
   
   <li><strong>Member Gender</strong></li>
       <ul>
           <li><strong>males are:</strong></li>
                <ul>
                    <li>more likey to travel from 500 to 1500m</li> 
                    <li>more likey to be between 20 - 30 year old</li>
                    <li>more likey to travel a duration of 0 to 500s</li>
                </ul>
           <li><strong>Female are:</strong></li>
                <ul>
                    <li>more likey to travel from 500 to 2000m</li>
                    <li>more likey to be between 20 - 30 year old</li>
                    <li>more likey to travel a duration of 0 to 1000s</li>
                </ul>
           <li><strong>Others are:</strong></li>
                <ul>
                    <li>more likey to travel from 500 to 2000m</li>
                    <li>more likey to be between 20 - 40 year old</li>
                    <li>more likey to travel a duration of 0 to 1000s</li>
                </ul>
        </ul>


## Key Insights for Presentation

   >Distribution of Trip Durations:
Trip Durations in the dataset take on a very large range of values. Number of Trips values first increases starting from around 8000 values to 12500 values at peak around 600 seconds but then starts to fall below at 2000 values.

>Distribution of User Age:
In the case of age, the distribution is more concentrated between 20 to 40 years old.
