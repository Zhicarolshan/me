This week I have learned "pivot_table.plot(kind='bar', stacked=True)" This line creates a bar plot from the pivot table.
second, "stacked=True" shows this option creates a stacked bar chart, where the bars for each region are stacked on top of each other to show the total number of dwellings, with each segment of the bar representing a different type of building.
Third, "figsize=(14, 8)" sets the size of the figure to be 14 inches wide and 8 inches tall, ensuring that the plot is large enough to be easily readable.
Forth,"pd.to_datetime(df['Date'])" shows this function converts the 'Date' column in the DataFrame df to a DateTime object.
Fifth, "df. groupby('Date')" groups the data by the 'Date' column. Since the 'Date' column is now in DateTime format, this groups the data by each unique date.
Sixth, The resulting time_series_data is a pandas Series where the index is the date and the values are the total number of dwellings for that date.
