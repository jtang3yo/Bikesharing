# Des Moines Bikesharing Analysis 
Tableau

## Overview of Project 
Now that we've gotten a good idea of how to create our story, there is still some more work to be done to convince investors that a bike-sharing program in Des Moines is a solid business proposal. To solidify the proposal, one of the key stakeholders would like to see a bike trip analysis.

For this analysis, you’ll use Pandas to change the "tripduration" column from an integer to a datetime datatype. Then, using the converted datatype, you’ll create a set of visualizations to:

Show the length of time that bikes are checked out for all riders and genders Show the number of bike trips for all riders and genders for each hour of each day of the week Show the number of bike trips for each type of user and gender for each day of the week. Finally, you’ll add these new visualizations to the two you created in this module for your final presentation and analysis to pitch to investors.

  1. Deliverable 1: Change Trip Duration to a Datetime Format
  2. Deliverable 2: Create Visualizations for the Trip Analysis
  3. Deliverable 3: Create a Story and Report for the Final Presentation

## Resources and Tools 
* Data Source: NYC_CitiBike_Challenge_starter_code.ipynb, NYC_Citibike_Challenge.ipynb and 201908-citibike-tripdata.csv
* Data Tools: Jupyter Notebook, CSV, Tableau 
* Software: Jupyter Notebook and Tableau 2021.2.0

## DELIVERABLE 1: Change Trip Duration to a Datetime Format
Using Python and Pandas functions, you’ll convert the "tripduration" column from an integer to a datetime datatype to get the time in hours, minutes, and seconds (00:00:00). After you convert the "tripduration" column to a datetime dataytpe, you’ll export the DataFrame as a CSV file to use for the trip analysis in Deliverable 2. 

### Analysis 
  1. The data in the "tripduration" column is converted to a datetime datatype and has the correct time format. 
    * Read csv file with pandas and import into a DataFrame, check the data types of the DataFrame. 
   citibike_df<img width="1048" alt="citibike_df" src="https://user-images.githubusercontent.com/82353749/126548311-f1330cb8-0aa1-4b6f-b324-197cd6a779f4.png">
    * Convert the 'tripduration' column to datetime datatype
   convert to datetime datatype<img width="1016" alt="convert to datetime datatype" src="https://user-images.githubusercontent.com/82353749/126548533-97756bcb-2b99-4028-a7a0-5f18cdf90037.png">
   2. Export the Dataframe as a new CSV file without the index with citibike_df.to_csv('citibike_201908_update.csv'). 

## DELIVERABLE 2: Create Visualizations for the Bike Sharing Trip Analysis

### Deliverable requirements: 
* How long bikes are checked out for all riders and genders.
* How many trips are taken by the hour for each day of the week, for all riders and genders.
* A breakdown of what days of the week a user might be more likely to check out a bike, by type of user and gender.

### Create the Checkout Times for Users Viz 
Graph the length of time that bikes are checked out for all riders: 
checkout time by user <img width="1036" alt="checkout time by user " src="https://user-images.githubusercontent.com/82353749/126551940-0bb80f3f-6b40-4953-a759-35bafb679d2f.png">

### Create the Checkout Times by Gender Viz
Graph the length of time that bikes are checked out for each gender: 
checkout times by gender<img width="1045" alt="checkout times by gender" src="https://user-images.githubusercontent.com/82353749/126553894-d7cd4b8c-ab44-420f-bf95-663a8da11525.png">

### Create the Trips by Weekday for Each Hour Viz 
Graph the number of bike trips by weekday for each hour of the day as a heatmap: 
trips by weekday by hours <img width="1031" alt="trips by weekday by hours " src="https://user-images.githubusercontent.com/82353749/126554031-8a788f6e-4771-4192-bf11-37e6ecd25bcf.png">
trips by weekday by hour with value<img width="1040" alt="trips by weekday by hour with value" src="https://user-images.githubusercontent.com/82353749/126559356-fd3fda9d-3efb-4283-98fa-6b30f6b2abd9.png">


### Create the Trips by Gender (Weekday per Hour) Viz
Graph the number of bike trips by gender for each hour of each day of the week as a heatmap: 
trips by gender<img width="1036" alt="trips by gender" src="https://user-images.githubusercontent.com/82353749/126555833-37876854-1758-45e4-b2fc-4fe1972f0f7f.png">
trips by gender with value<img width="1042" alt="trips by gender with value" src="https://user-images.githubusercontent.com/82353749/126559763-57fce570-bb4b-4332-80e5-ea4d5f1091ea.png">


### Create the User Trips by Gender by Weekday Viz
Graph the number of bike trips by gender for each hour for each day of the week as a heatmap:
user trips by gender<img width="1036" alt="user trips by gender" src="https://user-images.githubusercontent.com/82353749/126555981-111be329-16c5-463b-a2ed-0a05072e35cb.png">
user trips by gender with value<img width="1036" alt="user trips by gender with value" src="https://user-images.githubusercontent.com/82353749/126559973-977a681d-7b54-4569-999d-b1de569e4d2b.png">

## DELIVERABLE 3: Create a Story and Report for the Final Presentation

### CUSTOMERS DASHBOARD 
customers dashboard<img width="1251" alt="customers dashboard" src="https://user-images.githubusercontent.com/82353749/126561340-359f0566-85b6-472f-95d7-34e052255c72.png">
### GENERAL TRIP DATA 
general trip data<img width="1250" alt="general trip data" src="https://user-images.githubusercontent.com/82353749/126561496-e87f690d-bd6f-4c92-9616-d122bd964a5a.png">
### TRIPS BY TOP USE 
trips by top use<img width="1254" alt="trips by top use" src="https://user-images.githubusercontent.com/82353749/126561711-d2cf1ff7-7a5c-4b57-b8c8-601dd271f70f.png">
### INVENTORY DASHBOARD
inventory<img width="1247" alt="inventory" src="https://user-images.githubusercontent.com/82353749/126561843-4afc18e7-a0c9-4e5d-8c11-645494c85130.png">
### TOP 10 STARTING AND ENDING LOCATIONS 
top 10 locations <img width="1248" alt="top 10 locations " src="https://user-images.githubusercontent.com/82353749/126562054-ea867391-e76a-4f62-8c5e-8ca98714cfed.png">

## TABLEAU PUBLIC URL
[Final Analysis of BikeSharing](https://public.tableau.com/app/profile/jing.tang/viz/DesMoines_BikeSharing/CUSTOMERS?publish=yes)


