# Project 1: Electrical Vehicles Research

Group Members: Wing Lui, Ge Shen, Dashrath Bhandari, Sushil Baskota, Jingbo Zhao

## Project Summary:

In the past 10 years, the fuel price was very unstable (56% increased) compared to the electricity price (33% increased). Therefore, we are interested to investigate is electrical vehicles (EV) more worth buying to the general buyers compared to traditional vehicles, and in a bigger scale, comparing the electric vehicles markets in both global and Australia. This small study started with understanding the enginee performance of electrical and traditional vehicles. Then, we investigated the global and Australian EV sales market, which suggested that Austrlian EV market growth was falling behind compared to the other developed countries. Finally, we demonstrated that insufficient EV charging stations in Austrlia might be a potiental reason to slow down the EV growth in Australia.

---

#### Comparsion of fuel and electricity price (Dashrath Bhandari)


#### Eneginee Performance of EV and traditional vehicles (Ge Shen)


#### Global EV market sales (Sushil Baskota)


#### Austrlian EV market sales (Jingbo Zhao) 
The file [EV_Market_Analysis.ipynb](https://github.com/Kongfufack/Project_1_EV/blob/main/EV_Market_Analysis.ipynb) is the main script that I was working on. The first part of this script is to cleanup the dataset I've got [Total_vehicles_registered_in_the_ACT](https://github.com/Kongfufack/Project_1_EV/blob/main/Dataset/Total_vehicles_registered_in_the_ACT.csv). Basically filtered it by "SEDAN", "PETROL", "DIESEL", "ELECTRIC", and also modified the date and extract the year for each row of dataset. And then the bar chart of year vs. car sales with logarithmic scaled had been plotted in different colours. Subsequently, three sets of data from different countries was merged into one single dataframe and plotted in one graph. z-score normalization was used to compare across different countries. By looking at the trends of the data, I decided to adopt the exponential regression to see the correlation between year and the sales. As a conclusion, ACT is following the same trend with the other sample regions. If the tendency remains, we would expect an exponential growth in the next few years in Australia

#### Charging Stations in Australia (Wing Lui)
The analysis of charging stations in Australia is in [geoapify API](https://github.com/Kongfufack/Project_1_EV/blob/main/geoapify_API.ipynb). [Goeapify (API)](https://www.geoapify.com/) is utilised to identify the location of charging stations across the country (Australia). [The longitudes and latitudes of Australia cities](https://github.com/Kongfufack/Project_1_EV/blob/main/Dataset/Australia_city.csv) are used for the params in Geoapify. The fee requirement and the locations of each charging stations are extracted from the API responses and stored in [charging station csv file](https://github.com/Kongfufack/Project_1_EV/blob/main/output_data/charging_station.csv). The API data demonstrated that the coverage of charging stataions is insufficient and will avoid people who like road trip to purchase a EV. By comparing the API data and [the official data in Electric vehicle council](https://github.com/Kongfufack/Project_1_EV/blob/main/Dataset/Public_charging_infrastructure.csv), we found out that a lot of charging stations information were missing in the API. Also, there is no offical data or easy way to locate nearby charging station, which will be a big draw back to the general buyers.

---
For a better visualisation for our findings, please check our [power point slide](https://github.com/Kongfufack/Project_1_EV/blob/main/Project_1_EV.pdf).

## Referneces:
API: Geoapify

Please check the [reference](https://github.com/Kongfufack/Project_1_EV/blob/main/Dataset/reference.csv) to find all the sources of csv file 
