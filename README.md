# Tableau
## Tableau and Python
## Overview of the statistical analysis:
In this module, I have used data visualization software Tableau to present a business proposal for a bike-sharing company. I have used data from the Citi Bike program in New York City. The data was download will be contained in a flat file, a CSVFirst, I have used use Pandas to change the datatype of the "tripduration" column from an integer to a datetime datatype to get the time in hours and minutes. See NYC_Citibike_Challenge.ipynb

## Results
Deliverable 1: Change Trip Duration to a Datetime Format To convert the 'tripduration' column to datetime datatype, I used the following code citibike_tripdata_df['tripduration'] = pd.to_datetime(citibike_tripdata_df['tripduration'], unit='s'). Unit 's' represent seconds. I further export the Dataframe as a new CSV file without the index, by using the following code citibike_tripdata_df.to_csv(r'C:\Users\Jared\Module15\bikesharing\Starter_Code\citibike_tripdata1.csv', index=False). See NYC_Citibike_Challenge.ipynb.

## Deliverable 2: Visualizations for the Trip Analysis link to Trip Analysis dashboard

The Dashboard below is an analytical view of the following

- Number of bikes checked out by duration for all users
- Number of bikes that are checked out by duration for each gender by the hour and by per hour
- A heatmap was created to show the number of bike trips for each hour of each day of the week
- A heatmap was created to show the number of bike trips by gender for each hour of each day of the week, and is filtered by gender
- A heatmap was created to show the number of bike trips for each type of user and gender for each day of the week, and is filtered by user and gender


## Deliverable 3: A Story and Report for the Final Presentation link to Story for dashboard
Based on the trip analysis, Males were the highest of all the genders per bike that has '0' hours trip duration at over 108K. On Monday and Tuesday between 5:00 pm - 6:00 pm Males had the highest stop time and on Thrudays male had the highest subscription for user trip.

## Summary
Link to Trip Duration by weekday and time

Based on the the static Thursdays during the hours for 8:00 am, 5:00 pm and 6:00 pm has the highest trips. Overall Mondays, Tuesday and Thursdays during the hours for 8:00 am, 5:00 pm and 6:00 pm are the the best days for a trips for all genders while Wednesday is the least poplar day.
