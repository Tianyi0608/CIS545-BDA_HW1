# CIS545-BDA_HW1:
Data wrangling and analysis on flights data
1. Extract and clean data from csv format to pandas dataframe (tabular data)
2. Clean tabular data remove unnecessary info, change types of columns, merge dataframe
3. Use beautifulsoup to load, then find and clean text data with tags in html format
4. Remove useless info (e.g.'[edit]'), split data, select data
5. Remove stopwords, change it to dataframe, change string date to datetime
6. Store those dataframe to sql
7. Retrieve dataframe from sql
8. Compute the flight routes out of PHL and JFK
9. Calculate the busiest airports
10. Calculate active_airlines, different_airlines, missing_flights
11. Calculate the highest incident rate airlines called risky_df
12. Calculate the highest delay or cancelled rate airlines called delayed_cancelled_df
13. Find the most matched (has most common values) tow columns in two dataframes use Jaccard distance and select the most matched two columns
14. Merge airlines_df and delayed_cancelled_df based on the most matched two columns (add airline names to delayed_cancelled_df) called delayed_cancelled_ext_df
15. Merge delayed_cancelled_ext_df and risky_df on the airline names to find the very bad airlines ( high accident, delay, cancelled rate)
