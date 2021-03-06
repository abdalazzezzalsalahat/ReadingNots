# Pandas

> **pandas:** *Is a software library written for the Python programming language for data manipulation and analysis.*


> **pandas is like Excel in Python: it uses tables (namely DataFrame) and operates transformations on the data. But it can do a lot more.**

#### What kind of data does pandas handle?


> *When using a Python dictionary of lists, the dictionary keys will be used as column headers and the values in each list as columns of the DataFrame *  



##### data frame 

> *A DataFrame is a 2-dimensional data structure that can store data of different types (including characters, integers, floating point values, categorical data and more) in columns. It is similar to a spreadsheet, a SQL table or the data.frame in R.*


> *The table has 3 columns, each of them with a column label. The column labels are respectively Name, Age and Sex.*

> *The column Name consists of textual data with each value a string, the column Age are numbers and the column Sex is textual data.*

##### How do I select a subset of a DataFrame?
> *To select a single column, use square brackets [] with the column name of the column of interest.*

> > *Each column in a DataFrame is a Series. As a single column is selected, the returned object is a pandas Series.*


**`DataFrame.shape`** :

>*an attribute (remember tutorial on reading and writing, do not use parentheses for attributes) of a pandas Series and DataFrame containing the number of rows and columns: (nrows, ncolumns).*

>  **A pandas Series is 1-dimensional and only the number of rows is returned.**


 ##### How do I filter specific rows from a DataFrame?


> *To select rows based on a conditional expression, use a condition inside the selection brackets [].*

#### How to create plots in pandas?
> *To plot a specific column, use the selection method of the subset data tutorial in combination with the `plot()` method.*

* Hence, the `plot()` method works on both Series and DataFrame.


##### How to create new columns derived from existing columns?

> *To create a new column, use the [] brackets with the new column name at the left side of the assignment.*

#### How to calculate summary statistics?

> *The statistic applied to multiple columns of a DataFrame (the selection of two columns return a DataFrame, see the subset data tutorial) is calculated for each numeric column.*


