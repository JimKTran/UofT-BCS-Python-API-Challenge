# WeatherPy Homework
## _Submitted November 03, 2020_
### _By: Jim Tran_

![equatorsign](/..Images/equatorsign.png)

*The main objective of the Pymaceuticals homework assignment is to develop pandas scripts and matplotlib to analyze the results of tumor volumes as a result of different drug regimen across a population of mice. Given 2 raw data files in csv format; the 'Mouse_metadata.csv' and the 'Study_results.csv'.  The [Mouse_metadata](Images/MouseMetadata.png) data has 249 records describe by each unique 'Mouse ID' with their 'Drug Regimen', their 'Sex', 'Age' and 'Weight'. The [Study_results](Images/StudyResults.png) data is categorized with 'Mouse ID' along with columns for 'Timepoints, 'Tumor Volume' and 'Metastatic Sites'.  The 2 datasets were merged on Mouse ID to consolidate the data columns to determine the final total number of mice after the duplicate data from [mouse_ID_989](Images/DuplicatedMouseData.png) is removed resulting in a clean dataset with 1,880 unique records and 248 total mice count as an additional mouse ID g989 is found in index and also removed.*

*Next, the data is further manipulated and calculated to show the total number of unique mice tested on each drug regimen using [pandas](Images/PandasBarGraph.png) bar graph and [matplotlib](Images/MatplotlibBarGraph.png) bar graph; this is to show that there is no difference between the 2 methods.  Pie graphs from [pandas](Images/PandasPieGraph.png) and [matplotlib](Images/MatplotlibPieGraph.png) methods is used to show the total percentage of female to male mice in the study*

*Each unique Mouse ID is then merged with the clean data for 4 specific drugs and the results of final tumor volume on each mouse:* 
  * Capomulin
  * Ramincane
  * Infubinol
  * Ceftamin
  
*This dataset is further investigated with [quartiles](Images/Quartiles.png), outliers and then graphed on [boxplots](Images/Boxplots.png).  The third boxplot (Infubinol) show there is an outlier for the drug.*

*Additionally, a line graph is used to display tumor volumes vs. time points on selected Mouse ID w914 treated with Capomulin.  The [line_graph](Images/Lineplot.png) show downward trend between tumor volume and time points; as average tumor volumes decrease as time points increase.  This may suggest that the Capomulin may be an effective drug for treatment over time. 

*Lastly, mouse weight is measured against the average tumor volume for all mice treated with Capomulin.  The [scatter_graph](Images/ScatterPlot.png), there is an upward trend between average tumor volume and weight. Average tumor volume increases as weight also increases, suggesting a possible correlation between the metrics. The dataset is correctly display as the average tumor volume for each mouse is close the overall mean of 40.675 and median of 41.558 for Capomulin. And the [regression_graph](Images/ScatterWithRegression.png) show the data is relatively closely fitted on the scatter plot and there is a strong relationship with evidence of an r square of ~0.8.*

*This analyis was built using this work and [code](https://github.com/JimKTran/UofT-BCS-Matplotlib-Challenge/blob/master/pymaceuticals_starter.ipynb)*
