# Python Pandas data examples  
### EDA examples

## - EDA_election_data_time_series.ipynb
## Pandas Time series with Election Data
Exploratory Data Analysis examples - Part 2
For a lecture on Python tools for data scientists, I prepared few data used cases, to demonstrate pandas,numpy and matplotlib functionality. In this tutorial, US Election data is used. The data is published by the Federal Election Commission, and can be downloaded here: https://www.fec.gov The election data website, contain many data sets, with election information. Data about Candidates, Committees, fund raising transactions, contributors information, etc.

## pandas_groupby_titanic.ipynb
## Pandas Groupby explained with Titanic
### Group By: split-apply-combine
in many situations we want to split the data set into groups and do something with those groups. This is called "group by" process. Formally, by “group by” we are referring to a process involving one or more of the following steps:

* **Splitting** the data into groups based on some criteria. 
* **Applying** a function to each group independently. 
* **Combining** the results into a data structure, usually into DataFrame, or column which is Series.
<br>

Out of these, the split step is the most straightforward, usually we split by the different values of some feature.<br>
In the apply step, we might wish to one of the following:

* **Aggregation** functions like sum or count, statistical functions like mean or std and custom functions.

* **Transformation**: perform some group-specific computations and return a "list" of values - like-indexed object. For example to Filling Nan's within specific value to each group.

* **Filtration** discard some groups. For example, discard groups with only a few members. Filter outliers based on the group sum or mean.
<br>
Lets View examples for the above cases.As demonstration data, we use Titanic data. Download from kaggle, or use sample example from git.


Source: 
* https://pandas.pydata.org/pandas-docs/stable/groupby.html
