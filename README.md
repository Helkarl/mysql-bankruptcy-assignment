# mysql-bankruptcy-assignment
In this learning project I used MySQL to solve the assignment.
The assignment was to calculate how many years longer a company can operate with profit, assuming a trend of a 20% decrease each year will continue and be constant. 
The output was asked to be ordered in years from smallest to largest, and show each years profit including the year the profit gets to a negative number. 
Assuming the year is 2024 and the total operating income $1.000.000.

The query is handling two main tasks:
1.	Retrieve existing data from a 'financials' table.
2.	Simulate future years by calculating the revenue decline until the profit becomes negative, stopping at that first negative profit year.
