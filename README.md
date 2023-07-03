**Background**
You've just joined Pymaceuticals, Inc., a new pharmaceutical company that specializes in anti-cancer medications. Recently, it began screening for potential treatments for squamous cell carcinoma (SCC), a commonly occurring form of skin cancer.

As a senior data analyst at the company, you've been given access to the complete data from their most recent animal study. In this study, 249 mice who were identified with SCC tumors received treatment with a range of drug regimens. Over the course of 45 days, tumor development was observed and measured. The purpose of this study was to compare the performance of Pymaceuticals’ drug of interest, Capomulin, against the other treatment regimens.

The executive team has tasked you with generating all of the tables and figures needed for the technical report of the clinical study. They have also asked you for a top-level summary of the study results.

**Codes**
This script merged both of the mouse data and study result into one for better analysis.
First, it calculates the total number of mouse and find the duplicate mouse and clean them from the data that we want to analyse. And then calculates the statistic summary from the clean data and grouped by the drug regimen.

To better visualize these codes, bar chart is created to observe between two important data which is drug regimen and timepoints and population of data is also visualised by the composition of the mouse gender data into a pie chart.

To further analyse the data, Quartiles, Outliers and Boxplots are created to visualise between drug regimen and tumor volume. Line chart is created for mouse b742 for the treatment of drug Capomulin, this shows downward line and to observe correlation between tumor volume with mouse weight it shows in the scatter plot and regression line.

**Analysis**
Effectiveness of Drug Regimens between the 4 analysed, Capomulin and Ramicane are showing promising result reducing tumor volumne compared to Infubinol and Ceftamin.
Significant differenze in sampel size between Capomulin and Ramicane compared to Infubinol and Ceftamin, this should be taken into account when interpreting the result.
Gender distribution between male and female are almost equal amount in the study.
Potential outlier in Infubinol drug regimen in the analysis of tumor volume, this indicates anomalies and needs to be investigated.
Mouse treated with Capomulin seems to be reducing tumor size over time, this suggest this drug has positive effect.
There is a positive relationship between Mouse weight and Tumor volume, where the scatter plot and linier regression within the Capomulin regimen indicates, mouse with higher weights tend to have larger tumor volumes.

Shout out to redeat17 for the codes that I referred to.
