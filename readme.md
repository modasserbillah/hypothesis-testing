## Are university towns housing prices less affected by recession?

In this data analysis project, we will formulate a hypothesis around this question, gather and process required data and finally test our hypothesis.

### Strategy

We will use 3 datasources for this project. 
1. We will use GDP data from Bureau of Economic Analysis, US Department of Commerce, the GDP over time of the United States in current dollars (using the chained value in 2009 dollars), in quarterly intervals, in the file gdplev.xls. We will use this data to determine recession periods. For this project, we will only look at GDP data from the first quarter of 2000 onward.

2. We will use housing price data from the Zillow research data site. There is housing data for the United States. In particular the datafile for all homes at a city level, 'City_Zhvi_AllHomes.csv', has median home sale prices at a fine grained level.

3. We will use a list of university towns collected from Wikipedia to divide the housing price data in two sets as university towns and non-university towns. We have this data in the 'university_towns.txt' file.

So, we will use the above mentioned data sources and manipulate and tranform them to test our hypothesis.

### Hypothesis
#### University towns have their mean housing prices less affected by recessions.

### Required Definitions
* A _quarter_ is a specific three month period, Q1 is January through March, Q2 is April through June, Q3 is July through September, Q4 is October through December.
* A _recession_ is defined as starting with two consecutive quarters of GDP decline, and ending with two consecutive quarters of GDP growth.
* A _recession bottom_ is the quarter within a recession which had the lowest GDP.
* A _university town_ is a city which has a high percentage of university students compared to the total population of the city.
