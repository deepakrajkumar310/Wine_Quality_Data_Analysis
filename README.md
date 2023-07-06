# Wine_Quality_Data_Analysis
First, we have gone through and understood the data.
Then we imported various libraries using import command. These libraries include NumPy, Pandas, Matplotlib and Seaborn.
Then we loaded the data using pd.read_csv() function.
We then observed the information and summary of the columns using info() and describe() functions.

Later we performed Exploratory Data Analysis (EDA) on all the columns including Numerical and Categorical columns.
Also, some of these columns were explored together.
All the insights were provided against exploration of each column.

Later we did Data Wrangling.
We have checked for duplicate values and found there are some duplicate rows in the data. They were removed using drop_duplicates() function.
Also the columns have been checked for null values using isnull() function. It is found that there are few null values in the columns and they have been filled using fillna() function.
The outliers (i.e., extreme values) have been handled using filtering functions.
