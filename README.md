# Power_BI Visualization 

# Project 1: Vehicle Registration in all States in Malaysia

## Data Source and Introduction
This Power BI visualization project utilized data from https://data.gov.my/ which is an open source database that houses data catalogues by the government of Malaysia and specifically the 
- data catalogue (Vehicle Registration Transactions: Cars), which records car registration transactions from 2000 to the present year 31st July 2024. The link to the dataset can be viewed
through the following URL: https://data.gov.my/data-catalogue/registration_transactions_car

## How is this data produced?
This dataset contains the actual transactional records of all cars registered with the Road Transport Department (JPJ) since 2000, excluding any personal identifiable data (note: no personal
data as defined by Act 709 is ever handled or even received by the data.gov.my team in the process of producing this dataset). Under Malaysian law, all vehicles must be registered with JPJ and
be assigned a registration plate number before they can be used on the road.

## Dashboard Objective

This dashboard visualization may help some companies understand their customers better as the preference of fuel type, car brand and model and also the selection of colour of the vehicle in which
some car maker companies and car insurance institutions to predict the trend of cars that might have increase in sales based on the categories mentioned earlier and the selected date range to be analyzed
is from 1st January to 31st July 2024 as a more recent trend analysis.

This is important because of the arrival of new electric car technologies such as electric cars and preference to foreign brands are entering the Malaysian automotive market and this dashboard
will allow companies to view the how consumer behaviour regarding car selection is influence by different factors and this can help car makers both local and foreign brands to better prepare
when taken into account of designing and promoting their next car model or make improvement to their current range of car models to help increase sales trends for the Malaysian market.


## Dashboard visualization production steps:

Step 1 : Load data into Power BI Desktop using dataset is a csv file option

Step 2 : Open power query editor & in view tab under Data preview section, check "column distribution", "column quality" & "column profile" options.

Step 3 : It was observed that in none of the columns errors & empty values were present.

Step 4 : Remove underscore and capitalize the first letter of words of each column as part of the data preparation process. 

Step 5 : The DAX function Total Cars = COUNT(cars_2024[maker]) is created to calculated the number of total cars for a certain period

Step 6 : In the report view, under the view tab, dashboard theme was selected.

Step 7 : Chart and design were selected and configured for visualization.

Step 8 : Funnel, stacked area, clustered column, ribbon type chart were selected to represent total percentage of vehicle registration by model, vehicle registration by colour, 
vehicle registration by vehicle type, vehicle registration by year, vehicle registration by vehicle by brand(maker) vehicle registration by State or through JPJ portal. 

Step 9 : Visual filters (Slicers) were added for categories "State" for 1 slicer and "Vehicle Type"  for another slicer.

Step 10 : Filter selection based on time period (1 January 2024 to 31 July 2024) for data gathering purposes. 

## Dashboard visualization summary for selected time period (1 January 2024 to 31 July 2024)
From the visualization selection - it can be summarizes that most car registrations in Malaysia from 1 January 2024 to 31 July 2024, consists of the following car categories: 

Petrol fuel type vehicle remained in the popular choice of fuel type vehicle within the time period selected.  

Top 3 popular vehicle brands such as Proton, Perodua & Toyota vehicles tends to be the primary choice of purchase and registration within the time period selected. 

Top 3 popular vehicle colour registration within the time period selected -  White (12,918), Grey(11,943) and Silver(8,291)

Most registration Car vehicle brand - Proton Saga with 6.6k registration 

Most registration Jeep vehicle brand - Proton X50 with 2.1k registration

Most popular Multi Purpose vehicle brand - Perodua Alza with 2.3k registration

Most popular Pickup 4x4 vehicle brand - Toyota Hilux with 3.0k registration

Most popular Van brand -  Toyota Alphard with 3.3k registration





