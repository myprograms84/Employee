# Employee


#include <iostream>
#include <string>
#include "Employee.h"

using namespace std;

int main()
{
	//declare and initialize array index constant
	const int NUM_EMPLOYEES = 3;

	//declare array object of type Employee 
	Employee employeesAug[NUM_EMPLOYEES];

	//initialize array with provided data
	employeesAug[0].setEmployeeData = "Bob", 30000, 0.10;
	employeesAug[1].setEmployeeData = "Joe", 20000, 0.10;
	employeesAug[2].setEmployeeData = "Jack", 50000, 0.20;

	//print array data for array using a loop
	for (int i = 0; i < NUM_EMPLOYEES; i++)
	{
		employeesAug[0].print();
		employeesAug[1].print();
		employeesAug[2].print();
	}

	//declare a variable to save raise data into
	double raise;
	int x;

	//print array data for array using a loop
	for (int x = 0; x < 5; x++)
	{
		cout << "Enter an array location and the amount of the raise: ";
		cin >> employeesAug[x] >> raise;
		if (raise = 0)
		{
			cout << employeesAug[x].setEmployeeData.Employee::taxRate;
		}
	}
	
	//print array data for array using a loop
	for (int i = 0; i < NUM_EMPLOYEES; i++)
	{
		employeesAug[0].print();
		employeesAug[1].print();
		employeesAug[2].print();
	}

	system("pause");
	return 0;
}
