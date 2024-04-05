# matplotlib-northwestern-bootcamp <br>
**Uploaded all Module 5 Class activities for future reference including** <br>
  Module 5 - Data Visualization - Class 1, includes intro to matplotlib, navigate pyplot interface, create line/bar/pie charts and scatter plots, change appearance, and identify basic plot configuration options<br>
  Module 5 - Data Visualization - Class 2, includes create plots using dataframe.plot method, summarize advantages and disadvantages of this method, use pandas to analyze complex dataset and chart corresponding visualizations <br>
  Module 5 - Data Visualization - Class 3, includes caculating statistics using Python, plot, characterize, and quantify normally distributed datset with Python, identify outliers, differentiate sample and populations, define and quantify correlation, calculate and plot linear regression <br>
<br>
**Submission for Module 3 Challenge** <br>
Sources: Used support from Tutor and edX Learning Assistant as indicated to complete assignment <br><br>
**Prepare the Data (20 points)** <br>
  The datasets are merged into a single DataFrame. (6 points) - see first cell, 'combined_data'
  <br>
  The number of mice are shown from the merged DataFrame. (2 points) - see second cell, 'unique_mice_ids' <br>
  Each duplicate mice is found based on the Mouse ID and Timepoint. (6 points) - see third cell, 'duplicate_mice' <br>
  A clean DataFrame is created with the dropped duplicate mice. (4 points) - see fourth cell, 'cleaned_mice_data' <br>
  The number of mice are shown from the clean DataFrame. (2 points) - see fifth cell, 'original dataframe length' vs. 'cleaned dataframe length' <br><br>
**Generate Summary Statistics (15 points)**<br>
  The mean of the tumor volume for each regimen is calculated using groupby. (2 points) - see sixth cell, 'summary_stats_table' <br>
  The median of the tumor volume for each regimen is calculated using groupby. (2 points)  - see sixth cell, 'summary_stats_table' <br>
  The variance of the tumor volume for each regimen is calculated using groupby. (2 points)  - see sixth cell, 'summary_stats_table' <br>
  The standard deviation of the tumor volume for each regimen is calculated using groupby.  - see sixth cell, 'summary_stats_table' (2 points)<br>
  The SEM of the tumor volume for each regimen is calculated using groupby. (2 points)  - see sixth cell, 'summary_stats_table' <br>
  A new DataFrame is created with using the summary statistics. (5 points)  - see sixth cell, 'summary_stats_table' <br><br>
**Create Bar Charts and Pie Charts (15 points)** <br>
  A bar plot showing the total number of timepoints for all mice tested for each drug regimen using Pandas is generated. (4.5 points)  - see 8th cell, 'drug_regimen_counts' <br>
A bar plot showing the total number of timepoints for all mice tested for each drug regimen using pyplot is generated. (4.5 points) - see 9th cell, 'drug_regimen_counts' <br>
A pie plot showing the distribution of female versus male mice using Pandas is generated. (3 points) - see 10th cell, 'gender_distribution' <br>
A pie plot showing the distribution of female versus male mice using pyplot is generated. (3 points) - see 11th cell, 'gender_distribution' <br><br>
**Calculate Quartiles, Find Outliers, and Create a Box Plot (30 points)** <br>
A DataFrame that has the last timepoint for each mouse ID is created using groupby. (5 points) - see 'last_timepoint' <br>
The index of the DataFrame is reset. (2 points) - see 'last_timepoint' <br>
Retrieve the maximum timepoint for each mouse. (2 points) - see 'last_timepoint' <br>
The four treatment groups, Capomulin, Ramicane, Infubinol, and Ceftamin, are put in a list. (3 points) - see 'treatments_list' <br>
An empty list is created to fill with tumor volume data. (3 points) - see 'tumor_volume_data' <br>
A for loop is used to display the interquartile range (IQR) and the outliers for each treatment group (10 points) - see 'for treatment in treatments_list' <br>
A box plot is generated that shows the distribution of the final tumor volume for all the mice in each treatment group. (5 points) - see 'plt.boxplot(x = tumor_volume_data...) <br><br>
**Create a Line Plot and a Scatter Plot (10 points)** <br>
A line plot is generated that shows the tumor volume vs. time point for one mouse treated with Capomulin. (5 points) - see 'plt.plot(capomulin_data...)' <br>
A scatter plot is generated that shows average tumor volume vs. mouse weight for the Capomulin regimen. (5 points) - see 'plt.scatter(x=mouse_weight...)' <br><br>
**Calculate Correlation and Regression (10 points)** <br>
The correlation coefficient and linear regression model are calculated for mouse weight and average tumor volume for the Capomulin regimen. (10 points)- see 'plt.scatter(x=mouse_weight...)' & plt.plot(mouse_weight...) <br>
