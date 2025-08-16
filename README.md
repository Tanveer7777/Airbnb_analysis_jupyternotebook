--Project Goals

Load and explore Airbnb listings dataset.

Handle missing values and clean the data.

Visualize the following key business questions:

--Data Cleaning Steps

Checked for missing values using isnull().sum()

Filled or dropped missing data based on context

Converted data types (e.g., price to float, date to datetime)

Removed outliers where necessary

--Questions Answered in the Notebook
1️. What is the distribution of listing prices?

Visualized using histograms and boxplots

Identified price range, skewness, and outliers

2️. How are different room types distributed?

Used bar plots to compare frequency of room types (e.g., Entire home, Private room, Shared room)

3️. What is the relationship between price and room type?

Visualized using boxplots and violin plots

Found average prices per room type and pricing patterns

4️. How has the number of reviews changed over time?

Converted date columns to datetime

Grouped data by month/year

Line plot to show review trends over time
