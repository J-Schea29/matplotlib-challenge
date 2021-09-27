# matplotlib-challenge

For this project, I was required to analyze mouse tumor treatment data. In order to do this, I had to

1.) Check the data for any mouse ID with duplicate time points and remove any data associated with that mouse ID.

2.) Use the cleaned data for the remaining steps.

3.) Generate a summary statistics table consisting of the mean, median, variance, standard deviation, and SEM of the tumor volume for each drug regimen.

4.) Generate a bar plot using both Pandas’s DataFrame.plot() and Matplotlib’s pyplot that shows the total number of measurements taken for each treatment regimen throughout the course of the study.

5.) Generate a pie plot using both Pandas’s DataFrame.plot() and Matplotlib’s pyplot that shows the distribution of female or male mice in the study.

6.) Calculate the final tumor volume of each mouse across four of the most promising treatment regimens: Capomulin, Ramicane, Infubinol, and Ceftamin. Calculate the quartiles and IQR and quantitatively determine if there are any potential outliers across all four treatment regimens.

7.) Using Matplotlib, generate a box and whisker plot of the final tumor volume for all four treatment regimens and highlight any potential outliers in the plot by changing their color and style.

# Observations
From my analysis I have drawn three take aways.

1.) Capomulin and Ramicane are more sucessful at reducing tumor size than any of there competetors. This maybe result of greater research already haven been done for these drugs given that they also have the highest measurments taken

2.) For the mouse b128, tumor treatment rapidly increased after the timepoint 25. This sugests that a certain amount of time is needed for sucessful treament.

3.) There is a strong correlation between tumor volume and mouse weight (.84 to be precise). This is clearly seen also with the points of the scatter plot gathered closly around linear regression line. 
