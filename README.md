# HEROESOFPYMOLI

# The pandas library is imported as well as the data (purchase_data.csv).
# The top of dataframe is displayed.

# Player Count
# The total number of players is displayed.

# Purchase Analysis (Total)
# A data frame is created and the number of unique items is determined.
# The average price, the number of purchases and total revernues is calculated.
# The columns are formatted.

# Gender Demographics
# A dataframe is created for unique players.
# The number of male, female and undisclosed are determined for gender.
# A total count is calculated, followed by percent for each player and this is added to the dataframe.
# The columns are formatted.

# Purchasing Analysis (Gender)
# groupby person and sum the total price
# Using GroupBy in order to separate the data into fields according to "Gender" values
# Use describe to visualize the data
# filter on 'count' and 'mean'
# groupby gender and the sum pri
# groupby gender and then take the mean
# rename 'count' to 'Purchase Count' and 'mean' to 'Average Purchase Price'
# format 'Purchase Count' to integer
# create the dictionary to format all float columns to dollars with two decimal points
# format the dataframe with the appropriate format
# print the dataframe with the appropriate format

# Age Demographics
# rename the original dataframe to one for age and drop duplicates
# Establish bins for ages   
# Create the names for the five bins
# Categorize the existing players using the age bins. Hint: use pd.cut()
# Calculate the numbers and percentages by age group
# use a data function to visualize the data
# Create a list of the headers
# use a data function to visualize the data
# filter so it is only count
# get the total count
# rename the header to 'Total Count' from 'Purchase ID, count'
# get the percent for each age group and add to the dataframe
# Add the percents to the dataframe
# format all columns to dollars with two decimal points
# print the dataframe with the appropriate format
# Display Age Demographics Table

# Purchase Analysis (Age)
# rename the original dataframe to one for age
# Establish bins for ages   
# Create the names for the five bins
# Run basic calculations to obtain purchase count, avg. purchase price, avg. purchase total per person etc.
# Calculate the numbers and percentages by age group
# Create a summary dataframe to hold the results
# filter for the 'count' and average purchase price
# groupby gender and then sum price
# for each age range, divide 'Total Purchase Value' by the total number of unique players to create 'Avg Total Purchase per Person'
# rename ('Purchase', 'count') to 'Purchase Count' and ('Price', 'mean') to 'Average Purchase Price'
# format 'Purchase Count' to integer
# format all columns to dollars with two decimal points
# print the dataframe with the appropriate format
# Display the summary data frame

# Top Spenders
# rename the original dataframe to one for age
# group by SN
# Create a summary dataframe to hold the results
# filter for the 'count' and average purchase price
# groupby gender and the sum pri
# Sort in descending order based on "Total Purchase Value" column
# rename 'count' to 'Purchase Count' and 'mean' to 'Average Purchase Price'
# format 'Purchase Count' to integer
# create the dictionary to format all float columns to dollars with two decimal points
# format the dataframe with the appropriate format
# print the dataframee

# Most Popular Items
# Retrieve the Item ID, Item Name, and Item Price columns
# Group by Item ID and Item Name
# Perform calculations to obtain purchase count, average item price, and total purchase value and 
# create a summary data frame to hold the results
# Sort in descending order based on "Total Purchase Value" column
# rename 'count' to 'Purchase Count' and 'mean' to 'Average Purchase Price'
# format 'Purchase Count' to integer
# format all columns to dollars with two decimal points
# print the dataframe with the appropriate format
# Display a preview of the summary data frame

# Most Profitable Items
# Sort the above table by total purchase value in descending order.
# # rename 'count' to 'Purchase Count' and 'mean' to 'Average Purchase Price'
# format 'Purchase Count' to integer
# format all columns to dollars with two decimal points
# create the dataframe with the appropriate format
# Display a preview of the data frame
