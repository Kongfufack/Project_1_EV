# Project_1_EV

Group Members: Wing Lui, Ge Shen, Dashrath Bhandari, Sushil Baskota, Jingbo Zhao

Project Title: Electrical Vehicles Research

Project Description:
- Australia EV Market Analysis By country/region
- EV Infrastructure Analysis
- Environmental Impact Analysis


Rough Breakdown Of Task:
1. Collect and share data resources by each group member 21/01-23/01/2023
2. Select data together then merge/clear the table together 24/01/2023
3. Produce graph/figures/codes to analysis the data 25/01-30/01
4. Draw the conclusions 31/01/2022
5. Prepare presentation 1/02/2022 -2/02/2022
6. Final Presentation2/02/2022

Delegation of the Project:
Wing Lui - 

Ge Shen - 

Dashrath Bhandari - 

Sushil Baskota - 

Jingbo Zhao - 
The file EV_Market_Analysis.ipynb is the main script that I was working on. The first part of this script is to cleanup the dataset I've got Total_vehicles_registered_in_the_ACT.csv. Basically filtered it by "SEDAN", "PETROL", "DIESEL", "ELECTRIC", and also modified the date and extract the year for each row of dataset. And then the bar chart of year vs. car sales with logarithmic scaled had been plotted in different colours. Subsequently, three sets of data from different countries was merged into one single dataframe and plotted in one graph. z-score normalization was used to compare across different countries. By looking at the trends of the data, I decided to adopt the exponential regression to see the correlation between year and the sales. As a conclusion, ACT is following the same trend with the other sample regions. If the tendency remains, we would expect an exponential growth in the next few years in Australia


---
## Referneces:
API: Geoapify
Please check the [reference](https://github.com/Kongfufack/Project_1_EV/blob/main/Dataset/reference.csv) to find all the sources of csv file 
