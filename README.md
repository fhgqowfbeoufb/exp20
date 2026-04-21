# exp20
AIM
To explore and apply real-world data analysis techniques using Python for examining COVID-19 pandemic data through processes such as data cleaning, preprocessing, aggregation, visualization, and trend analysis with the help of Pandas, NumPy, and Plotly.
THEORY
Data analysis involves gathering, refining, transforming, and interpreting data to derive meaningful insights. In this study, a real-world COVID-19 dataset containing information on confirmed, recovered, and death cases across various countries and states was analyzed using Python libraries like Pandas and NumPy.
The dataset was initially preprocessed by removing irrelevant columns and converting data into appropriate formats such as datetime and numerical types. Additional metrics, such as active cases, were derived from existing data. Further analysis included grouping, filtering, sorting, and aggregating data to obtain country-wise and state-wise statistics.
To enhance understanding, interactive visualizations—such as choropleth maps—were created using Plotly to illustrate the global distribution of cases. Time-series analysis was also conducted to observe daily growth patterns and trends. This kind of real-world data analysis is crucial for identifying patterns in disease spread, comparing regions, and supporting informed decision-making through data-driven insights.
ONE-LINE EXPLANATIONS OF FUNCTIONS USED


read_csv() – Imports data from a CSV file into a DataFrame.


head() – Displays the initial rows of the dataset for quick inspection.


drop() – Eliminates unnecessary columns from the dataset.


info() – Provides a summary of column names, data types, and non-null values.


astype() – Converts columns to appropriate data types.


max() – Identifies the maximum value in a column, such as the most recent date.


groupby() – Organizes data into groups based on specific categories.


sum() – Computes total values within grouped data.


reset_index() – Converts grouped indices back into standard columns.


value_counts() – Counts the occurrences of unique values.


nunique() – Returns the number of distinct values in a column.


unique() – Lists all unique entries in a column.


fillna() – Handles missing data by replacing null values.


sort_values() – Arranges data in ascending or descending order.


iloc[] – Accesses data using integer-based indexing.


choropleth() – Generates an interactive geographical map based on data values.


shape – Displays the dimensions of the dataset (rows and columns).


CONCLUSION
In conclusion, this experiment successfully demonstrated the application of Python in real-world COVID-19 data analysis. It involved cleaning large datasets, deriving new metrics such as active cases, analyzing region-wise statistics, performing time-based trend analysis, and creating interactive visualizations. Overall, it highlighted the effectiveness of data science techniques in understanding real-world problems and extracting actionable insights.
