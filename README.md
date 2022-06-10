# Student_performance_analysis
STUDENT PERFORMANCE DATA SET:
We import the required libraries like NumPy, pandas, seaborn to perform data analysis based on the tasks given.
1)	In the first question we find the percentage and add to a new column to the existing data frame by using a simple formula for percentage calculation for each student / each row. We found the total by .describe() function.
2)	We found the mode for parental level of education. We replaced all the numeric data with the average that was found by .mean() function. Inside another function .fillna(). We then did .dropna() which removes the null value rows
3)	We plotted a box plot for reading score; we found it to be normal distribution whose two unique values are it has same value for its central tendencies and always shows a symmetric bell curve. There certain outliers under the minimum value.
4)	We performed the grading system for the column percentage.
5)	By using .groupby() function and .plot.bar() function.
1_a) We performed simple random sampling with random.choice()
1_b) We found the stratified data based on race
1_c) .sem() function was applied on a & b

