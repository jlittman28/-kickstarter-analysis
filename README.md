# -kickstarter-analysis
# Kickstarting with Excel

## Overview of Project
Data analysis is necessary for a business to maintain a competitive edge. The client is looking to levelset their fundraising goal against industry competitors.

### Purpose
To provide the client (Louise) with comparable campaign launch dates and their respective fund goals to make informed decisions about their business.

## Analysis and Challenges


### Analysis of Outcomes Based on Launch Date
We were provided a dataset of fundraising goals and their respective outcomes for various categories. In aggergating and analyzing outcomes of Theater's based on launch dates, we needed to first (through the modules) convert the Unix Time into date. This was a new concept to me, learning about the EPOCH (commencement of the UNIX Time). Then, we needed to create a PIVOT Table, followed by a line chart with markers to present the data. See chart below

![image](https://user-images.githubusercontent.com/85204128/122644332-aedf7b00-d0e2-11eb-9ecc-366a350b93f6.png)


### Analysis of Outcomes Based on Goals
We were provided a dataset of fundraising goals and their respective outcomes for various categories. In aggergating and analyzing outcomes of based on Goal Thresholds, we needed to count the goal targets for respective outcomes using Excel's COUNTIFs Function. Then, we were tasked with creating a line chart to present our findings. 

![image](https://user-images.githubusercontent.com/85204128/122644290-72138400-d0e2-11eb-9159-ddfa64c888ea.png)

### Challenges and Difficulties Encountered

# Challenges/Difficulties of Outcomes Based on Launch Date
Although I did not have any difficulties myself creating the filtered PIVOT and respective Line Chart, the below two tasks could prove to be difficult. 

1. Sort outcome column in descending order // A user may look to filter in More Sort Options which would cause the months to not be in Chronological order. 
2. Establishing Months // When droping in a date datatype field into a pivot table, Excel will GROUP the date to display QUARTERS (Q) and YEARS (YR). There are two ways to UNGROUP in order to display only months. Either you could drag the QUARTER and YEAR fields outside the table OR you can right click the PIVOT on date field and UNGROUP the Q and YR.

![image](https://user-images.githubusercontent.com/85204128/122644386-ef3ef900-d0e2-11eb-9f6e-18324904db33.png)


# Challenges/Difficulties of Outcomes Based on Launch Date
Although I did not have any difficulties preparing the data, writing the formulas to create the ranges of Goals between an upper and lower bounds may be cumbersome without knowing excel's syntax. For all text values in a look up formula, specifically in in this case, the operators need to be enclosed in quotes. A user can create the bounds either by enclosing the value inside the quotes with the operator, or by enclosing the operator in quotes separately and then using an ampersand sign to join a cell range, which I used for the upper/lower bounds.

![image](https://user-images.githubusercontent.com/85204128/122644451-3331fe00-d0e3-11eb-9f35-440ad4a36b22.png)


## Results

- What are two conclusions you can draw about the Outcomes based on Launch Date?
	1. It appears there are similarities in the peaks and valleys for all months except for December, for Successful/Failed Outcomes.
	2. Whereas Successful Outcome experiences a steep peak in may at 111 Succesful fundraisers, and steeper declines in coming months, Fails/Canceled outcomes have minimal peaks/valleys with the results relatively distributed throughout the respective months.
- What can you conclude about the Outcomes based on Goals?
	1. The data is relatively in-line between Successful/Failed projects
- What are some limitations of this dataset?
	1. The formulas used to count ranges of Goal Outcomes, could be stored within the Kickstarter dataset instead of in a separate tab. This will allow for more consoldiated/concise analysis.
- What are some other possible tables and/or graphs that we could create?
	1. Box Plot to more clearly define outliers in the range 
	2. Histogram to easily compare data across both analyses
