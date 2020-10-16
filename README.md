# pandas-challenge
Homework week 4

Import pandas library and load schools_complete.csv and students_complete.csv

Read files with pandas and use the merge function to combine into a single dataset

Checked for any incomplete values using the count function and determined there were none.

Use the nunique function on schools to find the total number of schools.

Use the count function on students assuming there may be some duplicate values where different students have the same name.

Create a dataframe with only the school name and budget to remove the variaton of the other columns and group by the min of budget since the number is repeated in every row.  

Find the sum of each school's total budget.

Calculate the average scores for math and reading by using the mean function.

Use the loc function with a condition for scores of greater than equal to 70 in math reading and both.

Create a dictionary of the data and pass the summary totals through with titles for each data point.

Create a dataframe using the dictionary.