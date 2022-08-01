# Overview
This analysis uses Python and SQLAlchemy to query a SQLite file containing weather data for Hawaii. I analyzed the 2010-2018 weather data to see when the best weather for surking occurs throughout the year. to get a good sample, I looked at two months, June and December.


**June** 

To begin analysis for June, I queried the Measurement table to retrieve June temperatures for every year that data was available (2010-2018). 

![June df](https://user-images.githubusercontent.com/105829106/182052478-79c691f9-d1c8-4e64-991f-dc132f8c8047.PNG)

**December**

I simply refactored the code June code to work for the December analysis. I started with querying all December temperatures. 

![December df](https://user-images.githubusercontent.com/105829106/182052523-ad8499c5-bc86-4b4a-8dae-1bd203f9a55e.PNG)


## Results

**June**

![June Summary](https://user-images.githubusercontent.com/105829106/182052551-a6345cb4-dd11-4a7e-9733-53178b84f7e7.PNG)


**December**

![December Summary](https://user-images.githubusercontent.com/105829106/182052561-a410dc6c-719a-4177-baae-c601a53857e0.PNG)


* There are not significant differences between the weather during June and December in Hawaii. This is to be expected given Hawaii's tropical climate. The mean June temperature is roughly 75 degrees, and the mean December temperature is 71. 

* The minimum temperature is lower in December. 
The minimum temperature in June was 64 degrees compared to the minimum temperature in December, which was 56 degrees. 56 degrees is definitely cold enough to deter people from surfing. It may be beneficial to potentially shutdown the shop during the winter when the temperature is too cold.

