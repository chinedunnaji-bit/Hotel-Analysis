# Hotel Dataset Analysis

This repository contains Python code to analyze a hotel dataset. The dataset includes information about hotel bookings, such as guest demographics, booking details, and hotel ratings. The analysis aims to provide insights into various aspects of the hotel business, including guest demographics, booking patterns, and factors influencing booking prices.

## Dataset Description

The dataset used for analysis is stored in an Excel file named "Hotel Dataset.xlsx". It was obtained from [DataFrik](https://datafrik.co/#/datasets), a platform for sharing and exploring datasets. The dataset includes the following columns:

- **Check-in Date**: The date when guests checked into the hotel.
- **Check-out Date**: The date when guests checked out of the hotel.
- **Time**: The time of booking.
- **No. of Days**: The duration of the stay.
- **Age**: The age of the guests.
- **Gender**: The gender of the guests.
- **Origin Country**: The country of origin of the guests.
- **State**: The state of origin of the guests.
- **Destination Country**: The destination country of the guests.
- **Payment Mode**: The mode of payment for the booking.
- **No. Of People**: The number of people in the booking.
- **Rooms**: The number of rooms booked.
- **Hotel Name**: The name of the hotel.
- **Hotel Rating**: The rating of the hotel.
- **Booking Price[SGD]**: The booking price in Singapore Dollars (SGD).
- **Discount**: The discount applied to the booking.
- **GST**: The Goods and Services Tax (GST) applied to the booking.
- **Profit Margin**: The profit margin of the booking.
- **Date of Booking**: The date of booking.
- **Booking Hour**: The hour of the booking.
- **Booking Day of Week**: The day of the week of the booking.

## Analysis Overview

The analysis includes the following steps:

1. **Data Loading and Cleaning**: Loading the dataset from the Excel file and performing initial data cleaning, including handling missing values and duplicates.
2. **Exploratory Data Analysis (EDA)**: Exploring the dataset to understand its structure and characteristics. This includes examining data distributions, identifying outliers, and visualizing relationships between variables.
3. **Feature Engineering**: Creating new features from existing ones, such as calculating the duration of stay and extracting hour components from booking times.
4. **Statistical Analysis**: Performing statistical analysis to understand the relationships between different variables, such as correlation analysis and distribution analysis.
5. **Visualization**: Creating visualizations, such as histograms, box plots, and heatmaps, to represent the data and identify patterns or trends.
6. **Insights and Conclusion**: Summarizing the findings from the analysis and drawing conclusions based on the insights gained.

## Requirements

- Python 3.x
- Libraries: pandas, numpy, matplotlib, seaborn

## Instructions

1. Clone this repository to your local machine.
2. Install the required libraries using pip or conda.
3. Run the Jupyter notebook or Python script to execute the analysis.
4. View the generated visualizations and insights in the notebook or script output.

## Results

The analysis provides insights into various aspects of the hotel business, including guest demographics, booking patterns, and factors influencing booking prices. Key findings include:

- Distribution of guest demographics (age, gender, origin country).
- Relationship between hotel ratings and booking prices.
- Impact of booking hour and day of the week on booking frequency.
- Distribution of booking prices across different payment modes.

## Conclusion

The analysis highlights important trends and patterns in the hotel dataset, which can be valuable for hotel management and marketing strategies. Further analysis and modeling can be performed to predict booking prices, identify customer segments, and optimize hotel operations.

## Additional Resources

- **Medium Article**: [Link to Medium Article](https://medium.com/@ebube45/06f0c3e575e5)
- **Tableau Visualization**: [Link to Tableau Visualization](https://public.tableau.com/app/profile/david.nnaji/viz/HotelDashBoard/HotelDashboard)
- **Data Source**: [DataFrik - Hotel Dataset](https://datafrik.co/#/datasets)