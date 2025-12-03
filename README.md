📌 Project Overview

This project presents a complete exploratory data analysis (EDA) of a large airline flights dataset containing 300,000+ rows and 12 columns of flight booking information scraped from a travel website.

The analysis covers:

Flight pricing patterns

Airline performance

Duration patterns

Travel time segments

Source/Destination city trends

Booking behavior based on days left

Economy vs Business class comparison

All analysis is performed using Python, Pandas, NumPy, Matplotlib, and Seaborn inside Jupyter Notebook.

📂 Dataset Description

The dataset contains:

Feature	Description
Airline	Name of the airline
Source City	City where the flight departs
Destination City	Final arrival city
Departure Time	Time slot of departure
Arrival Time	Time slot of arrival
Duration	Total duration of flight (hrs)
Days Left	Days before departure when booked
Class	Economy / Business
Price	Ticket price

Total Records: 300,153
Total Columns: 12

🛠️ Technologies Used

Python

Pandas

NumPy

Matplotlib

Seaborn

Jupyter Notebook

📊 Key Analysis Performed
✔️ 1. Data Cleaning

Removed unnecessary index column

Checked datatypes, missing values, and statistical summary

Validated dataset completeness

✔️ 2. Airline Frequency Analysis

Used value_counts() to identify which airlines operate the most flights.

✔️ 3. Departure & Arrival Time Patterns

Categorized flights into 6 time slots

Visualized most popular departure and arrival windows

✔️ 4. Source & Destination City Analysis

Identified most common routes

Visualized using horizontal bar charts

✔️ 5. Price Variation Analysis

Compared average ticket prices:

Across airlines

Across time slots

Across cities

Used groupby() + categorical plots

✔️ 6. Booking Trends (Days-Left Analysis)

Studied how ticket price changes as departure day approaches

Found interesting patterns & exceptions

✔️ 7. Economy vs Business Class Comparison

Filtered by travel class

Compared average prices for both segments

✔️ 8. Multi-condition Filtering

Example query used:

“Average price of Vistara Business-Class flights from Delhi to Hyderabad.”

📈 Visual Insights
<img width="643" height="522" alt="Screenshot 2025-12-03 152451" src="https://github.com/user-attachments/assets/b0e26e72-4d69-444c-98bc-d0afb25e1a87" />
<img width="634" height="525" alt="Screenshot 2025-12-03 152443" src="https://github.com/user-attachments/assets/e9ff326b-f738-4e60-9f59-2e8e8ae50d2e" />


⭐ Key Findings

Vistara operates the highest number of flights.

Delhi is the busiest source city; Mumbai the busiest destination.

Morning departures and Night arrivals dominate.

Late night flights are the cheapest.

Business class prices are significantly higher than Economy.

Ticket prices increase as travel day comes closer (except 1 day before).
🤝 Connect

If you like this project or have suggestions, feel free to connect!
