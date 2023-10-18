# Hotel-Booking-EDA-project
Have you ever wondered when the best time of year to book a hotel room is? Or the optimal length of stay in order to get the best daily rate? What if you wanted to predict whether or not a hotel was likely to receive a disproportionately high number of special requests? This hotel booking dataset can help you explore those questions! This data set contains booking information for a city hotel and a resort hotel, and includes information such as when the booking was made, length of stay, the number of adults, children, and/or babies, and the number of available parking spaces, among other things. All personally identifying information has been removed from the data. Explore and analyse the data to discover important factors that govern the bookings.
Project Summary -
In this project, we conducted an in-depth Exploratory Data Analysis (EDA) of a dataset containing hotel booking data. The project involved several key steps:

Data Preprocessing:

We started by cleaning the data, handling missing values, and converting columns to appropriate data types.

Data Transformation:

We created new columns to enhance the dataset's features and insights. A 'total_stay' column was added, which represents the total length of the stay by adding 'stays_in_weekend_nights' and 'stays_in_week_nights.' A 'total_people' column was created to calculate the total number of guests by summing 'adults,' 'children,' and 'babies.' Duplicate Handling:

We identified and removed around 30,000 duplicate rows to ensure data integrity.

Data Type Conversion:

We adjusted the data types of specific columns, such as converting 'children,' 'company,' and 'agent' to integers. We converted the 'reservation_status_date' column to a datetime data type. These data preprocessing and transformation steps prepared the dataset for analysis. The final dataset was ready for further exploration, analysis, and modeling, as needed for specific project objectives.

we visualised this data and created lots of chart and found some conclusion and insights which we will discuss.

Overall, this EDA project aimed to gain insights into the hotel booking data.
