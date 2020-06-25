### Project Overview

 Project Overview
In this project we load the data to a numpy array and add a new record on it . The parameter 'delimiter="," ' is set because the file that we are opening has extension CSV(Comma Separated Values).The parameter 'skip_header=1' is set because the first row of the data(which is called header) contains string values but in our numpy array we need only integers(Remember numpy array can only store data of a single data type)


### Learnings from the project

 Learnings from the project
Array Appending
Array Slicing
Array Filtering
Array Aggregation


### Approach taken to solve the problem

 Approach taken to solve the problem
1)Create a new array called 'age' by taking only age column(age is the column with index 0) of 'census' array. 2) Find the max age and store it in a variable called 'max_age'. 3)Find the min age and store it in a variable called 'min_age'. 4)Find the mean of the age and store it in a variable called 'age_mean'. 5)Find the standard deviation of the age and store it in a variable called 'age_std'. 6) Create four different arrays by subsetting 'census' array by Race column(Race is the column with index 2) and save them in 'race_0','race_1', 'race_2', 'race_3' and 'race_4' respectively(Meaning: Store the array where 'race'column has value 0 in 'race_0', so on and so forth) 7) Store the length of the above created arrays in 'len_0', 'len_1','len_2', 'len_3' and 'len_4' respectively 8) Find out which is the race with the minimum no. of citizens 9)Store the number associated with the minority race in a variable called 'minority_race'(For eg: if "len(race_5)" is the minimum, store 5 in 'minority_race' because that is the index of the race having the least no. of citizens ) 9)Create a new subset array called 'senior_citizens' by filtering 'census' according to age>60 (age is the column with index 0) 10)Add all the working hours(working hours is the column with index 6) of 'senior_citizens' and store it in a variable called 'working_hours_sum' 11)Find the length of 'senior_citizens' and store it in a variable called 'senior_citizens_len' 12)Finally find the average working hours of the senior citizens by dividing 'working_hours_sum' by 'senior_citizens_len' and store it in a variable called 'avg_working hours'.Print 'avg_working_hours' and see if the govt. policy is followed. 13)Create two new subset arrays called 'high' and 'low' by filtering 'census' according to education-num>10 and education-num<=10 (education-num is the column with index 1) respectively. 14)Find the mean of income column(income is the column with index 7) of 'high' array and store it in 'avg_pay_high'. Do the same for 'low' array and store it's mean in 'avg_pay_low'.


