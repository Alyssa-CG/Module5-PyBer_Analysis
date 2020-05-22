# PyBer Analysis Report

## Background and Results

### Purpose

This analysis of data from PyBer, a rideshare company, was conducted to evaluate any relationships between date, fare, number of drivers in the city, number of rides hired and types of cities where rides are hired.

### Technical Analysis

The aforementioned factors were all analysed using Python 3.7.8 (including the matplotlib, pandas, NumPy and SciPy libraries) in a Jupyter Notebook 6.0.3 environment. These tools were used to generate summary statistics, dataframes and a variety of charts to more easily summarise and visualise the trends in the data and ([code available here](https://github.com/Alyssa-CG/Module5-PyBer_Analysis/blob/master/PyBer_Challenge.ipynb)).

### Results and Summary

The data, as depicted below, has revealed that the urban cities generated the highest total fares, and the largest percentage of overall fare revenue for PyBer for 2019, compared to suburban and rural cities.

![Total Fare by City Type](https://github.com/Alyssa-CG/Module5-PyBer_Analysis/blob/master/Analysis/Fig8.png)

![Percentage of Total Fares by City Type](https://github.com/Alyssa-CG/Module5-PyBer_Analysis/blob/master/Analysis/Fig5.png)

As detailed in the summary dataframe below, urban cities are also associated with the highest number of rides and the highest number of drivers, however rural cities are associated with the highest fare per ride and the highest fare per driver.

![Ride Data Summary Dataframe](https://github.com/Alyssa-CG/Module5-PyBer_Analysis/blob/master/Analysis/ride_data_summary_df.png)

## Challenges Encountered and Overcome

### Challenges and Difficulties Encountered

The large amount of data was, at times, difficult to keep track of, setting an index as a datetime data type was trickier than setting the index as another data type and using methods not expressly covered by the course (pivot tables in python, fiveThirtyEight style, resample()) were all challenging, but satisfyingly rewarding to overcome.

### Technical Analyses Used

To maintain an understanding of what data had already been processed and calculated, variable names were as clear as possible and using the dir() function throughout was helpful for finding what variables had been defined.

![dir() function](https://github.com/Alyssa-CG/Module5-PyBer_Analysis/blob/master/Analysis/dir().png)

For setting the index as datetime data type, it was necessary to consult online as well as expert sources for tips. It was also useful to use the info() function to determine the data type for the index both before and after the change.

![info() function](https://github.com/Alyssa-CG/Module5-PyBer_Analysis/blob/master/Analysis/set%20index%20as%20datetime.png)

In order to address topics with which I was not familiar, it was important to learn from the links provided with the challenge, such as https://matplotlib.org/3.1.1/gallery/style_sheets/fivethirtyeight.html and https://pandas.pydata.org/pandas-docs/stable/reference/api/pandas.DataFrame.resample.html, while also searching for more sources as necessary, such as https://pandas.pydata.org/pandas-docs/stable/reference/api/pandas.pivot_table.html.

## Recommendations and Next Steps

Based on the data from different city types, I would tell V. Isualize that it looks like it may be worth hiring new rideshare drivers in suburban and especially rural cities, but it would be best to get information both on the cost per driver that PyBer incurs and the demographic of current riders by city type before making these decisions.

### Recommendations for Future Analysis

### Analyse cost of rideshare drivers

As the data has shown that urban cities generate the most revenue, but it is unclear if they generate the most profit, it would be beneficial to evaluate a dataset that includes the cost of drivers (commissions, etc.). Data can be grouped by city then total, per ride and per driver costs and returns can be calculated, which could then be presented in summary dataframes and line plots to inform decision-making.

### Demographic on current riders

PyBer can use demographic datasets to determine what age and other demographic groups use their services most, in which types of cities and when during the year they do. This information can be summarised in dataframes, and also compared for total rides and presented in a pie plot to show which demographics make up the highest percentages of rides, to inform marketing decisions.
