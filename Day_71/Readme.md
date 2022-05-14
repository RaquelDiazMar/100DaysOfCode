## Day 71 - Data Exploration with Pandas: College Major vs Your Salary

College degrees are very expensive. But, do they pay you back? Choosing Philosophy or International Relations as a major may have worried your parents, but does the data back up their fears? __PayScale Inc.__ did a year-long survey of 1.2 million Americans with only a bachelor's degree. We'll be digging into this data and use Pandas to answer these questions:

 - Which degrees have the highest starting salaries? 

 - Which majors have the lowest earnings after college?

 - Which degrees have the highest earning potential?

- What are the lowest risk college majors from an earnings standpoint?

- Do business, __STEM__ (Science, Technology, Engineering, Mathematics) or __HASS__ (Humanities, Arts, Social Science) degrees earn more on average?



Today you'll learn

 - How to explore a Pandas DataFrame

 - How to detect NaN (not a number) values and clean your data

 - How to select particular columns, rows, and individual cells

 - How to sort your data

 - How to group data by category

and so much more! Let's get started!



### Today's Learning Points

 - Use `.head()`, `.tail()`, `.shape` and `.columns` to explore your DataFrame and find out the number of rows and columns as well as the column names.

- Look for __NaN__ (not a number) values with `.findna()` and consider using `.dropna()` to clean up your DataFrame.

- You can access entire columns of a DataFrame using the square bracket notation: `df['column name']` or `df[['column name 1', 'column name 2', 'column name 3']]`

- You can access individual cells in a DataFrame by chaining square brackets `df['column name'][index]` or using `df['column name'].loc[index]`

- The largest and smallest values, as well as their positions, can be found with methods like `.max()`, `.min()`, `.idxmax()` and `.idxmin()`

- You can sort the DataFrame with `.sort_values()` and add new columns with `.insert()`

- To create an __Excel Style Pivot Table__ by grouping entries that belong to a particular category use the `.groupby()` method



