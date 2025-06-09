# projectZomato

## Zomato Data Analysis Using Python
- Do more restaurants provide online delivery compared to offline services?
- Which types of restaurants are most favored by the general public?
- What price range do couples prefer for dining out?

## Implementation for Zomato Data Analysis using Python.

- Importing necessary Python libraries.
We used Pandas, Numpy, Matplotlib and Seaborn libraries.
- Creating the data frame.
Convert the rate column to a float by removing denominator characters.
Checked for missing or null values to identify any data gaps.
- Data Cleaning and Preparation
- Exploring Restaurant Types
- Identify the Most Voted Restaurant
- Online Order Availability
- Checking the distribution of ratings from the rate column
- Analyze the approx_cost(for two people) column to find the preferred price range.
- Compare ratings between restaurants that accept online orders and those that don't.
- Find the relationship between order mode (online_order) and restaurant type (listed_in(type)).
-    pivot_table = dataframe.pivot_table(index='listed_in(type)', columns='online_order', aggfunc='size', fill_value=0): Created a pivot table counting restaurants by type and online order availability.


## Conclusion
Dining restaurants primarily accept offline orders whereas cafes primarily receive online orders. This suggests that clients prefer to place orders in person at restaurants butprefer online ordering at cafes.
