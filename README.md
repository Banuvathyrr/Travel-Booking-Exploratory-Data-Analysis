<h1 align="center">Travel Booking Exploratory Data Analysis and Insights</h1>

**Project Description:**  
This project involves the exploratory data analysis (EDA) of a travel booking dataset, aimed at deriving actionable insights and trends from booking and session data. The dataset contains information about bookings, sessions, and customer activities on a travel booking platform. The analysis covers various aspects of customer behavior, booking trends, and service usage, focusing on key metrics such as bookings, device usage, routes, and the relationship between search and booking activities.  

The project includes multiple stages of data processing, cleaning, and analysis to derive key insights, visualizations, and trends. The insights are used to understand customer preferences, booking patterns, and identify potential areas for platform improvement. The following steps are covered in this project:

**1. Data Discovery:**
- Loaded and explored two key datasets: Bookings.csv and Sessions.csv.
- Examined basic details like column types, data types, and missing values.
- Identified the unique counts of booking_id, session_id, and search_id.
  
**2. Data Cleaning:**  
- Checked for and removed duplicate entries from the sessions_data.  
- Handled missing values and performed appropriate data type conversion (e.g., date-time columns like booking_time, session_starting_time, and search_time).  
- Cleaned and merged the datasets on the common column booking_id.
  
**3. Data Analysis & Key Insights:**  
- Distinct Counts: Calculated the number of distinct bookings, sessions, and searches.  
- Sessions with Multiple Bookings: Identified sessions with more than one booking.  
- Booking Distribution by Day of Week: Analyzed and visualized booking distribution across days of the week using a pie chart.  
- Service-wise Booking and Gross Booking Value: Summarized the total number of bookings and gross booking value (INR) for each service.  
- Most Booked Route for Customers with More than One Booking: Identified the most booked route for customers with multiple bookings, based on the from_city and to_city.  
- Top 3 Departure Cities for Advance Bookings: Identified the top 3 cities with the highest average days to departure, provided there were at least 5 bookings from each city.  
- Heatmap of Numerical Data Correlations: Created a correlation heatmap to identify the most highly correlated numerical columns in the bookings data.  
- Most Used Device for Booking by Service: Identified the most used device types for bookings across different services.  
- Trends of Bookings by Device Type (Quarterly): Analyzed booking trends over time, by device type, at a quarterly frequency.  
- oBSR (Online Booking Success Rate) Analysis: Calculated the oBSR for each month, day of the week, and plotted its time series across dates.

**4. Visualizations:**
- Generated pie charts, bar charts, heatmaps, and time series plots to visualize key findings.  
- Plotted trends and distributions to aid in understanding booking behaviors and preferences.   
- Created time series analysis for the booking success rate (oBSR) across various time periods.  

**Technologies Used:**  
- Python Libraries: Pandas, Matplotlib, Seaborn  
- Data Processing & Analysis: Merging datasets, handling duplicates and missing values, data type conversions, and aggregation.  
- Visualization: Various plots, including pie charts, heatmaps, line charts, and time series analysis.

  
**Conclusion:**
This project provides a comprehensive overview of travel booking behavior, highlighting key metrics and insights that can be utilized for improving service offerings, marketing strategies, and platform optimization. By analyzing trends such as peak booking days, the most common routes, and customer preferences regarding device usage, this EDA can help stakeholders make data-driven decisions for enhancing customer experience and platform performance.

