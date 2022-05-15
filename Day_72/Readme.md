## Data Visualization with Matplotlib: Programming Languages

__Analyse the Popularity of Different Programming Languages over Time__

The oldest programming language still in use today is FORTRAN, which was developed in 1957. Since then many other programming languages have been developed. But which programming language is the most popular? Which programming language is the Kim Kardashian of programming languages; the one people just can't stop talking about? 

StackOverflow will help us answer this burning question. Each post on Stack OverFlow comes with a Tag. And this Tag can be the name of a programming language.

To figure out which language is the most popular, all we need to do is count the number of posts on Stack Overflow that are tagged with each language. The language with the most posts wins!

![image](../Day_72/image.png)

Today you will learn:

 - How to visualise your data and create charts with Matplotlib

 - How to pivot, group and manipulate your data with Pandas to get it into the format you want

 - How to work with timestamps and time-series data

- How to style and customise a line chart to your liking

The notebook goes about:

 - useage of `.groupby()` to explore the number of posts and entries per programming language

 - converted strings to Datetime objects with `to_datetime()` for easier plotting

 - reshaping our DataFrame by converting categories to columns using `.pivot()`

 - usage of `.count()` and `isna().values.any()` to look for __NaN__ values in our DataFrame, which we then replaced using `.fillna()`

 - creation of (multiple) line charts using `.plot()` with a for-loop

 - styling our charts by changing the size, the labels, and the upper and lower bounds of our axis.

 - adding a legend to tell apart which line is which by colour

 - smoothed out our time-series observations with `.rolling().mean()` and plotted them to better identify trends over time.
