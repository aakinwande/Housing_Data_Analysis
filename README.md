# Housing_Data_Analysis
Data Analysis Project! This project utilizes Python's powerful libraries, including Pandas, Seaborn, and Matplotlib, to perform data cleaning, transformation, and visualization tasks.


<h2>Introduction</h2>
This project focuses on analyzing data using various Python commands and functions. It involves tasks such as converting data types, adding and removing columns, filtering data, and visualizing missing values. The goal is to gain insights from the data and perform specific queries to extract meaningful information.


<h2>Commands and Functions</h2>
1.Importing Libraries<br />

-> import pandas as pd - To import the Pandas library.<br />
-> import seaborn as sns - To import the Seaborn library.<br />
-> import matplotlib.pyplot as plt - To import the Matplotlib library.


<h3>2. Data Handling with Pandas<br /</h3>

-> pd.read_csv('file.csv') - To import the CSV file into a Pandas DataFrame.<br />
-> df.count() - Counts the number of non-null values in each column.<br />
-> df.isnull().sum() - Detects missing values in the DataFrame.<br />
-> df.dtypes - Displays the datatype of each column.<br />
-> pd.to_datetime(df['Date_Time_Col']) - Converts the datatype of a Date-Time column to datetime[ns].


<h3>3. Data Transformation<br /></h3>

-> df['Time_Col'].dt.year - Creates a new column with only year values.<br />
-> df['Time_Col'].dt.month - Creates a new column with only month values.<br />
-> df.insert(index, 'new_column_name', new_column_values) - Inserts a new column at a specified position with values.<br />
-> df.drop(['Col_name'], axis=1, inplace=True) - Permanently drops a column from the DataFrame.<br />
-> df.groupby('Col_name') - Groups the DataFrame by unique values of a column.<br />
-> df[df['Col_1'] == 'Element1'] - Filters the DataFrame to access records where Col_1 equals 'Element1'.<br />
-> df.groupby('Col_1')['Col_2'].mean() - Creates groups based on Col_1 and applies a mean function on Col_2.


<h3>4. Data Visualization<br /></h3>

-> sns.heatmap(df.isnull()) - Visualizes missing values in a heatmap.<br />
-> plt.show() - Displays the plot.


<h3>5. Tasks Performed</h3>
-> Convert Datatype<br />
-> Add Columns<br />
-> Remove Columns<br />
-> Filter and Count Records<br />
-> Calculate Statistics<br />
-> Count Records with Condition<br />


<h2>Contributing</h2>
Contributions are welcome! Please fork this repository and submit a pull request for any enhancements or bug fixes.
