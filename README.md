# Employee
Write an Employee class.  It should be able to keep track of:
•	employee's name (string)
•	employee’s id number (int)
•	current salary (double)
•	tax rate (double)

The class should have methods to:
•	set all of the information (one or many methods)
•	ability to print employee information
•	give employee a raise (adding raise to salary)
•	calculate and return total taxes paid (calculate salary * tax rate)

Additionally, the employee id should be unique and should be managed with a static variable.

TestEmployee should contain main and will test your Employee class. 
•	Create an array of 3 employees. You may declare and initialize the data in one step.  Here is the information for each employee:
Name	Salary	Tax Rate	Id (should be set with static class variable, not a value passed into constructor)
Bob	30000	0.10	00001
Joe	20000	0.10	00002
Jack	50000	0.20	00003
•	Loop through the array and call print() for each account.
•	Loop for 5 times asking the user to enter an index into the employee array and a raise.   
o	If the raise amount is 0, then print the amount of taxes paid.
•	Loop through the array and call print() for each account.
Sample Run #1: (the highlighted text is what the user types) 
Bob(00001) $30000
Joe(00002) $20000
Jack(00003) $50000
index raise? 1 0

Taxes paid by will be $2000
index raise? 1 1000

index raise? 1 0

Taxes paid by will be $2100
index raise? 2 1500

index raise? 0 500

Bob(00001) $30500
Joe(00002) $21000
Jack(00003) $51500
Press any key to continue . . .
