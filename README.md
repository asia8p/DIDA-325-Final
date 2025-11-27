# Introduction

We are a team of analysts working for Washington, DC’s District Department of Transportation (DDOT) to identify how weather patterns affect bike ridership. We are looking at historical usage data to forecast bike rental demand in the Capital Bikeshare program. Analyzing this data allows the DDOT to understand Washington, DC’s mobility and how to introduce more efficient bike sharing systems to improve user satisfaction and increase the amount of annual tourists. For instance, by understanding bike ridership traffic, the DDOT can then know when and where to prioritize maintenance efforts on bikes in the summer at tourist locations or which locations to store bikes away in the winter when it is cold. Our goal is to gain a better understanding of features that may impact the rate at which bikes are rented in order to develop a more efficient system for all bike users with an emphasis on increasing the number of registered bike users.

The dataset is provided by Washington, DC’s Capital Bikeshare data, which is a bicycle sharing service that operates in Washington, DC. Capital Bikeshare recorded anonymized bike trip information from 2011 to 2012. This dataset combined trip information such as **date, year, season, and user type.** The dataset also merges Capital Bikeshare's information with the weather patterns of each rider’s bike trip, where each bikeshare user is classified as either registered or casual to determine how often they utilize this system. Having both rider and weather information can help us as analysts identify reoccuring patterns and determine the correlation they share. This will allow us to give reliable recommendations on how to increase the number of users and improve upon services to Washington DC's Department of Transportation, specifically for their Capital Bikeshare.

We plan on achieving this through exploring our four research questions:

**Research Question 1:** Are registered users more likely to ride in “bad” weather (3of weathersit) compared to casual riders?

**Research Question 2:** Does the month (mnth) affect the rate at which casual users and registered users rent bikes (casual and registered)?

**Research Question 3:** How can we accurately predict the number of registered bikers based on weather conditions (weathersit, temp, atemp, hum, windspeed)?

**Research Question 4:** How can we accurately predict the total number of bikes rented based on the time of year (year, month, holiday)?
