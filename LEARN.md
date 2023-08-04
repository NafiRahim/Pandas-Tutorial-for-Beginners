# A table listing some commonly used pandas functions along with their descriptions:

| Function Name           |  Description                                                                       |
|-------------------------|-----------------------------------------------------------------------------------|
| `pandas.DataFrame()`    | Creates a new DataFrame, a two-dimensional labeled data structure with columns of potentially different types. |
| `pandas.Series()`       | Creates a new Series, a one-dimensional labeled array capable of holding any data type. |
| `DataFrame.head()`      | Returns the first n rows of a DataFrame. Default value of n is 5.                 |
| `DataFrame.tail()`      | Returns the last n rows of a DataFrame. Default value of n is 5.                  |
| `DataFrame.shape`       | Returns a tuple representing the dimensions of the DataFrame (rows, columns).     |
| `DataFrame.info()`      | Prints a concise summary of a DataFrame, including the data types and memory usage. |
| `DataFrame.describe()`  | Show descriptive statistics of the DataFrame, such as count, mean, min, max, etc. |
| `DataFrame.columns`     | Returns the column labels of the DataFrame.                                       |
| `DataFrame.index`       | Returns the index (row labels) of the DataFrame.                                   |
| `DataFrame.loc[]`       | Accesses a group of rows and columns by label(s) or a boolean array.              |
| `DataFrame.iloc[]`      | Accesses a group of rows and columns by integer-based position(s).                |
| `DataFrame.drop()`      | Removes specified rows or columns from a DataFrame.                               |
| `DataFrame.isnull()`    | Checks for missing values in the DataFrame and returns a boolean mask.            |
| `DataFrame.fillna()`    | Fills missing values in the DataFrame with a specified value or method.            |
| `DataFrame.idxmax()`    | Returns the index of the row with the highest value in the specified column.       |
| `DataFrame.idxmin()`    | Returns the index of the row with the lowest value in the specified column.        |
| `DataFrame.sort_values()` | Sorts the DataFrame by the values in a specified column.                          |
| `DataFrame.rename()`    | Renames the index labels or column names of a DataFrame.                          |
| `DataFrame.drop_duplicates()` | Removes duplicate rows from a DataFrame.                                       |
| `DataFrame.concat()`    | Concatenates two or more DataFrames into a single DataFrame.                      |
| `DataFrame.merge()`     | Merges two DataFrames on a specified column.                                      |
| `DataFrame.plot()`      | Creates a plot of the specified column(s) of a DataFrame.                         |
| `DataFrame.groupby()`   | Creates a group that can be used to group a DataFrame by a specified column.      |
| `DataFrame.agg()`       | Aggregates data from a DataFrame.                                                 |
| `DataFrame.pivot_table()` | Creates a pivot table that groups and aggregates data from a DataFrame.         |
| `DataFrame.melt()`      | Converts a DataFrame from wide to long format.                                    |
| `DataFrame.stack()`     | Converts a DataFrame from wide to long format, stacking all columns into a single column. |
| `DataFrame.unstack()`   | Converts a DataFrame from long to wide format, unstacking a single column into multiple columns. |
| `pandas.crosstab()`     | Creates a two-way table that can show the frequency counts of multiple columns.   |