# Exploratory Data Analysis (EDA) -  Hotel Booking

Problem: The hotel wants to understand customer booking trends, behavior, and room preferences to increase revenue.

# Dataset Sources and Structure
source of the dataset
The dataset has been taken from Kaggle
Data Link
Dataset File Type: CSV

# Structure of the dataset
The dataset consists of 36,275 rows and 19 columns.

# Columns Information : 

1. Booking_ID: unique identifier of each booking
2. no_of_adults: Number of adults
3. no_of_children: Number of Children
4. no_of_weekend_nights: Number of weekend nights (Saturday or Sunday) the guest stayed or booked to stay at the hotel
5. no_of_week_nights: Number of week nights (Monday to Friday) the guest stayed or booked to stay at the hotel
6. type_of_meal_plan: Type of meal plan booked by the customer:
7. required_car_parking_space: Does the customer require a car parking space? (0 - No, 1- Yes)
8. room_type_reserved: Type of room reserved by the customer. The values are ciphered (encoded) by INN Hotels.
9. lead_time: Number of days between the date of booking and the arrival date
10. arrival_year: Year of arrival date
11. arrival_month: Month of arrival date
12. arrival_date: Date of the month
13. market_segment_type: Market segment designation.
14. repeated_guest: Is the customer a repeated guest? (0 - No, 1- Yes)
15. no_of_previous_cancellations: Number of previous bookings that were canceled by the customer prior to the current booking
16. no_of_previous_bookings_not_canceled: Number of previous bookings not canceled by the customer prior to the current booking
17. avg_price_per_room: Average price per day of the reservation; prices of the rooms are dynamic. (in euros)
18. no_of_special_requests: Total number of special requests made by the customer (e.g. high floor, view from the room, etc)
19. booking_status: Flag indicating if the booking was canceled or not.

# Data Cleaning
The dataset doesn't have any missing values or any duplicated values.

# Exploratory Data Analysis (EDA) 

# Data Overview:
dataset top 5 records
dataset last 5 records
Get the basic info about data
descriptive summary of the dataset
dataset size (rows + columns)
dataset sample
dataset shape (rows and columns)
dataset all columns
Define Unique Values per Column
all columns datatype
Create all column data type Table
Check missing values
Check dataset duplicate values

# Data Analysis - EDA:
Separated the dataset columns into numerical and categorical features
Observation: data have 14 numerical columns and 5 categorical columns
Univariate Analysis of Numerical Feature

Distribution plot → How many adults come to most bookings?
Observation of this analysis: The histogram shows that the most bookings have 2 adults.


Boxplot with avg_price_per_room → What is the price of a room if there are more adults?
Observation of this analysis: As can be seen from the boxplot, the more adults there are, the more avg_price_per_room increases.  When the number of adults increases to 2, the room prices rise, with the highest concentration of bookings around 540

Countplot → What % of bookings have kids?
Observation of this analysis: This plot shows that most of the time there are no children when booking a room, and very few people come with 1 or 2 kids.

Cancellation relation → Are bookings with children more likely to be cancelled?
Observation of this analysis: This chart shows that if bookings with kids are not as cancelled, then bookings without kids are not cancelled as much.

Distribution → How many nights do customers stay on weekends?

Compare with booking_status → whether long weekend booking cancellations are more frequent.
Observation of this analysis: Those who don't stay on weekend nights don't get canceled much.

Histogram → How long in advance is booking made?
Observation of this analysis: TMost of the people 0-9 dayes before booking made.

Pie chart → What % of guests repeat?
Observation of this analysis: This plot showing repeated guests percent label 1.256% and new guest percent label 97.4%

 Line plot → In which month are bookings higher (seasonality).
Observation of this analysis: October Month have the most booking and january Month have lowest booking.

Cancellation pattern → Which month has the most cancellations?
Observation of this analysis: October month have the most booking cancellations

Histogram → Which price range has the most bookings?
Observation of this analysis:  whcih room has Average price 90-109.99 , that room booking most

Popular room type
Observation of this analysis: Popular Room type is Room_Type 1

This analysis helps hotel management optimize room allocation, reduce cancellations, and provide personalized service to improve customer satisfaction and revenue.

# Tools Used:
Python (Pandas, NumPy, Matplotlib, Seaborn, Plotly)

Check my portfolio - https://meharinhasnapuspo.me
