# What we will learn

- Pandas 

The source of this summary [The first link](https://pandas.pydata.org/pandas-docs/stable/user_guide/10min.html)

The source of this summary [The second link](https://www.youtube.com/watch?v=dcqPhpY7tWk&t=391s)

______________________________________

## Pandas

**pandas is a software library written for the Python programming language for data manipulation and analysis. In particular, it offers data structures and operations for manipulating numerical tables and time series.with pandas you can manipulate model and analyze data,join data you can merge data , also reshape data** 

### How to Import the Pandas?

     import pandas as pd
     
     
### Object creation

*Each column in a DataFrame is a Series*

example:

      ages = pd.Series([22, 35, 58], name="Age")
      
      ages
          Out[6]: 
          0    22
          1    35
          2    58
          Name: Age, dtype: int64
          
### Viewing data

**The DataFrame.head() function in Pandas, by default, shows you the top 5 rows of data in the DataFrame. The opposite is DataFrame.tail(), which gives you the last 5 rows. Pass in a number and Pandas will print out the specified number of rows as shown in the example below. Head() and Tail() need to be core parts of your go-to Python Pandas functions for investigating your datasets**

### Missing Data

**Missing Data can occur when no information is provided for one or more items or for a whole unit. In Pandas missing data is represented by two value: Attention geek! Strengthen your foundations with the Python Programming Foundation Course and learn the basics**


### Merge

**Pandas provides a single function, merge, as the entry point for all standard database join operations between DataFrame objects**

#### we have to used the following parameters:

1. left − A DataFrame object.

2. right − Another DataFrame object.

3. on − Columns (names) to join on. Must be found in both the left and right DataFrame objects.

4. left_on − Columns from the left DataFrame to use as keys. Can either be column names or arrays with length equal to the length of the DataFrame.

5. right_on − Columns from the right DataFrame to use as keys. Can either be column names or arrays with length equal to the length of the DataFrame.

6. left_index − If True, use the index (row labels) from the left DataFrame as its join key(s). In case of a DataFrame with a MultiIndex (hierarchical), the number of levels must match the number of join keys from the right DataFrame.

7. right_index − Same usage as left_index for the right DataFrame.

8. how − One of 'left', 'right', 'outer', 'inner'. Defaults to inner. Each method has been described below.

9. sort − Sort the result DataFrame by the join keys in lexicographical order. Defaults to True, setting to False will improve the performance substantially in many cases.

### Grouping

**Pandas groupby is used for grouping the data according to the categories and apply a function to the categories. It also helps to aggregate data efficiently. Pandas dataframe. groupby() function is used to split the data into groups based on some criteria**

1. Splitting the data into groups based on some criteria

2. Applying a function to each group independently

3. Combining the results into a data structure

