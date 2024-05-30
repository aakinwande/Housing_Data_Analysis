# Housing_Data_Analysis
Data Analysis Project! This project utilizes Python's powerful libraries, including Pandas, Seaborn, and Matplotlib, to perform data cleaning, transformation, and visualization tasks.


<h2>Introduction</h2>
This project focuses on analyzing data using various Python commands and functions. It involves tasks such as converting data types, adding and removing columns, filtering data, and visualizing missing values. The goal is to gain insights from the data and perform specific queries to extract meaningful information.


<h2>Commands and Functions</h2>
Importing Libraries

import pandas as pd - To import the Pandas library.
import seaborn as sns - To import the Seaborn library.
import matplotlib.pyplot as plt - To import the Matplotlib library.
Data Handling with Pandas

pd.read_csv('file.csv') - To import the CSV file into a Pandas DataFrame.
df.count() - Counts the number of non-null values in each column.
df.isnull().sum() - Detects missing values in the DataFrame.
df.dtypes - Displays the datatype of each column.
pd.to_datetime(df['Date_Time_Col']) - Converts the datatype of a Date-Time column to datetime[ns].
Data Transformation

df['Time_Col'].dt.year - Creates a new column with only year values.
df['Time_Col'].dt.month - Creates a new column with only month values.
df.insert(index, 'new_column_name', new_column_values) - Inserts a new column at a specified position with values.
df.drop(['Col_name'], axis=1, inplace=True) - Permanently drops a column from the DataFrame.
df.groupby('Col_name') - Groups the DataFrame by unique values of a column.
df[df['Col_1'] == 'Element1'] - Filters the DataFrame to access records where Col_1 equals 'Element1'.
df.groupby('Col_1')['Col_2'].mean() - Creates groups based on Col_1 and applies a mean function on Col_2.
Data Visualization

sns.heatmap(df.isnull()) - Visualizes missing values in a heatmap.
plt.show() - Displays the plot.


<h2>Tasks Performed</h2>
Convert Datatype

Convert the datatype of the 'Date' column to Date-Time format.
Add Columns

Add a new column 'year' containing only the year extracted from a Date-Time column.
Add a new column 'month' as the second column in the DataFrame, containing only the month.
Remove Columns

Remove the 'year' and 'month' columns from the DataFrame.
Filter and Count Records

Show all records where 'No. of Crimes' is 0 and count the number of such records.
Calculate Statistics

Determine the maximum and minimum 'average_price' per year in England.
Find the maximum and minimum number of crimes recorded per area.
Count Records with Condition

Show the total count of records for each area where the average price is less than 100,000.


<h2>Contributing</h2>
Contributions are welcome! Please fork this repository and submit a pull request for any enhancements or bug fixes.
