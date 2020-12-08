# Matplotlib Challenge - Pymaceuticals



## Method

#### Initial Work

- Dependencies and Setup
- Study data files
- Read the mouse data and the study results
- Combine the data into a single dataset
- Display the data table for preview

#### Clean Up Work

* Checking the number of mice.
* Get a count to ID how many duplicate mice
* Get all the data for the duplicate mice
* Drop the duplicate mouse
* Checking the number of mice to verify

#### Summary Statistics

* Group the data by Drug Regimen.
* Calculated the mean, median, variance, standard deviation, and SEM of the tumor volume
* Assemble the resulting series into a single summary dataframe.
* Using the same grouped data, use the aggregation method to calculate mean, median, variance, standard deviation, and SEM of the tumor volume

#### Bar Charts

- Identify the total number of measurements taken on each drug regimen using value counts on drug regimen
- Plot the graph using .plot in pandas
- Plot the graph using .bar in matplotlib

#### Pie Charts

- Identify the distribution of gender using value counts on gender
- Plot the graph using .plot in pandas
- Plot the graph using .pie in matplotlib

#### Quartiles, Outliers and Boxplots

- Getting the last (greatest) timepoint for each mouse by grouping on mice and pulling the max  on timepoint
- Merge to original dataframe to get the tumor volume at the last timepoint
- Put specific drug treatments into a list for a for loop 
- Create empty list to fill with tumor volume data
- Locate the rows which contain mice on each drug treatment and subset based on the max timepoints created previously
- Get the tumor volumes
- Calculate the IQR
- Determine outliers using upper and lower bounds
- Print the IQR and where potential outliers stand
- Count the outliers of the above and below the upper bounds
- Print count of potential outliers
- Plot the graph

#### Line Plot

- Identify mouse treated with Capomulin
- Use chosen mouse from array to plot
- Plot the graph of tumor volume vs. time point

#### Scatter Plot

- Identify Capomulin data
- Getting the average (mean) tumor volume and weight for each mouse
- Plot the graph of average tumor volume vs. mouse weight

#### Correlation and Regression

- Calculate correlation mouse weight and average tumor volume
- Calculate linear regression model 
- Plot the graph with slope intercept for mouse weight and average tumor volume for the Capomulin regimen