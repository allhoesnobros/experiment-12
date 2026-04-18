# experiment-12
Roll No: 25070123125
EXP 12 : Study of Pandas Library
Theory
Pandas DataFrame

A DataFrame in Pandas is a two-dimensional labeled data structure with rows and columns. It is widely used for storing and analyzing structured data. DataFrames allow efficient handling of large datasets and support various operations such as filtering, grouping, and aggregation.

Reading CSV File (pd.read_csv())

The pd.read_csv() function is used to read data from a CSV (Comma Separated Values) file and convert it into a DataFrame. It is one of the most commonly used functions for importing datasets in data analysis.

value_counts() Function

The value_counts() function is used to count the frequency of unique values in a column. It helps in understanding the distribution of categorical data such as grades, gender, or categories.

Normalization (Percentage Distribution)

By using value_counts(normalize=True), we can calculate the relative frequency or percentage distribution of data. This helps in better interpretation of proportions rather than raw counts.

Cross Tabulation (pd.crosstab())

The pd.crosstab() function is used to compute a cross-tabulation of two or more variables. It is useful for analyzing relationships between categorical variables such as:

Gender vs Grade
Department vs Gender

It can also be normalized to show percentage relationships.

Data Filtering

Filtering is used to extract specific rows from a dataset based on conditions. For example, selecting only Electronics orders from a dataset helps focus analysis on a specific category.

Sorting Data (sort_values())

The sort_values() function is used to arrange data in ascending or descending order based on a column. Sorting improves readability and helps identify patterns in the dataset.

Creating DataFrame from Dictionary

A DataFrame can also be created using a Python dictionary. Each key represents a column, and its corresponding values represent the data entries. This method is useful when manually creating datasets.

Conclusion

Thus, the Pandas library was studied and implemented successfully. Various operations such as reading datasets, calculating frequency distributions, performing cross-tabulation, filtering data, and sorting were explored. The experiment demonstrated how Pandas simplifies data analysis and helps in extracting meaningful insights efficiently.
