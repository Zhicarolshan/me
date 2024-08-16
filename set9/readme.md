This week I start to sum up the number of dwellings by type and region.
firstly I have learned ' sns.barplot()', this function from the Seaborn library creates a bar plot
I have learned 'hue='Type_of_Building'', the hue parameter adds an additional dimension to the plot, dividing the bars within each region by the type of building.  
This allows me to compare the number of different types of dwellings within each region.
'plt. title('Number of Dwellings by Region and Type')' Set the title of the plot to 'Number of Dwellings by Region and Type'.
'plt. xlabel('SA2NAME')' Labels the x-axis as 'SA2NAME', indicating that it represents the regions. It is the same with the y-axis
region_type_aggregation.pivot() show the pivot() function creates a pivot table from the region_type_aggregation DataFrame.
