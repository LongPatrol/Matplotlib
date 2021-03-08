# Matplotlib

In this exercise, we are looking at data from a cancer drug trial. Several drugs were tested on lab mice to see the effect on the tumors of the mice. We ran some summary statistics and created various vizualizations to help in evaluating this study.

We found that:

1. The volume of the tumor has a strong correlation to the weight of the mouse
2. In at least one mouse on Capomulin, the volume of the tumor went down over the time the mouse was taking the drug.
3. The test subject mice were split about 50-50 male and female.


## Number of measurements taken per drug:

![Bar chart](https://github.com/LongPatrol/Matplotlib/blob/main/Images/Bar%20chart.png)

## Distribution of male and female mice:
![Pie chart](https://github.com/LongPatrol/Matplotlib/blob/main/Images/Pie%20chart.png)

## Distribution of tumor volume in most promising drugs:
![Box plot](https://github.com/LongPatrol/Matplotlib/blob/main/Images/Box%20plot.png)

## Example of one mouse's experience with Capomulin:
![Line graph](https://github.com/LongPatrol/Matplotlib/blob/main/Images/Line%20graph.png)


## Tumor volume in relation to mouse weight (Capomulin):
![Regression chart](https://github.com/LongPatrol/Matplotlib/blob/main/Images/Regression.png)

### Sources:

Drop duplicates:
https://pandas.pydata.org/pandas-docs/stable/reference/api/pandas.DataFrame.drop_duplicates.html

Filtering rows in a dataframe:
https://pandas.pydata.org/pandas-docs/stable/getting_started/intro_tutorials/03_subset_data.html

Dropping rows with specific values:
https://www.geeksforgeeks.org/drop-rows-from-the-dataframe-based-on-certain-condition-applied-on-a-column/

Dataframe from the columns of another dataframe:
https://stackoverflow.com/questions/34682828/extracting-specific-selected-columns-to-new-dataframe-as-a-copy

Standard error measure:
https://docs.scipy.org/doc/scipy/reference/generated/scipy.stats.sem.html

https://pandas.pydata.org/pandas-docs/stable/reference/api/pandas.core.groupby.GroupBy.sem.html

Rename a column:
https://stackoverflow.com/questions/19758364/rename-specific-columns-in-pandas

From <https://stackoverflow.com/questions/19758364/rename-specific-columns-in-pandas> 

Aggregate method:
https://pandas.pydata.org/pandas-docs/stable/reference/api/pandas.DataFrame.aggregate.html

Group by object:
https://pandas.pydata.org/pandas-docs/version/0.23.1/generated/pandas.core.groupby.DataFrameGroupBy.agg.html

Un-index a column:
https://stackoverflow.com/questions/20461165/how-to-convert-index-of-a-pandas-dataframe-into-a-column

Matplotlib bar labels:
https://matplotlib.org/3.1.1/gallery/ticks_and_spines/ticklabels_rotation.html

Matplotlib bar width:
https://matplotlib.org/3.3.3/api/_as_gen/matplotlib.pyplot.bar.html

Matplotlib legend:
https://www.datasciencemadesimple.com/bar-plot-bar-chart-in-python-legend-using-matplotlib/

Pandas charts:
https://pandas.pydata.org/pandas-docs/version/0.23.4/generated/pandas.DataFrame.plot.html

Pandas pie plot:
https://pandas.pydata.org/pandas-docs/stable/reference/api/pandas.DataFrame.plot.pie.html

Pyplot pie charts:
https://matplotlib.org/3.1.1/gallery/pie_and_polar_charts/pie_features.html

Referencing an index:
https://pandas.pydata.org/pandas-docs/stable/reference/api/pandas.DataFrame.index.html

Pyplot making the circle bigger:
https://stackoverflow.com/questions/29786807/how-to-make-a-pie-chart-smaller-with-matplotlib

Dropping rows based on multiple conditions:
https://stackoverflow.com/questions/29017525/deleting-rows-based-on-multiple-conditions-python-pandas

Appending:
https://www.w3schools.com/python/ref_list_append.asp

Type of object:
https://stackoverflow.com/questions/2225038/determine-the-type-of-an-object

Multiple boxplots in one figure:
https://matplotlib.org/gallery/pyplots/boxplot_demo_pyplot.html#sphx-glr-gallery-pyplots-boxplot-demo-pyplot-py

Subplot documentation:
https://matplotlib.org/3.3.3/api/_as_gen/matplotlib.pyplot.subplot.html


Changing the color of an outlier:
https://stackoverflow.com/questions/25075023/matplotlib-boxplot-outlier-color-change-if-keyword-sym-is-used
