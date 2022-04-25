# How does pandas deal with dates? 
#### 1. Convert strings to datetime.<br/>
Pandas has a built-in function called to_datetime() that can be used to convert strings to datetime.
#### 2. Assemble a datetime from multiple columns.<br/>
to_datetime() can be used to assemble a datetime from multiple columns as well. The keys (columns label) can be common abbreviations like [‘year’, ‘month’, ‘day’, ‘minute’, ‘second’, ‘ms’, ‘us’, ‘ns’]) or plurals of the same.
#### 3. Get year, month and day.<br/>
dt.year, dt.month and dt.day are the inbuilt attributes to get year, month , and day from Pandas datetime object.
#### 4. Get the week of year, the day of week, and leap year.<br/>
Similarly, dt.week, dt.dayofweek, and dt.is_leap_year are the inbuilt attributes to get the week of year, the day of week, and leap year.
#### 5. Get the age from the date of birth.<br/>
The simplest solution to get age is by subtracting year.
#### 6. Improve performance by setting date column as the index.<br/>
#### 7. Select data with a specific year and perform aggregation.<br/>
#### 8. Select data with a specific month and a specific day of the month.<br/>
#### 9. Select data between two dates.<br/>
#### 10. Handle missing values.<br/>
