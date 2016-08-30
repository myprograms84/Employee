# Employee


#include <iostream>
#include <string>
#include "Employee.h"

using namespace std;

//***************************/
// Initialize static member variable
// -- don't put static word here (only in .h)
int Employee::idNumber = 0000;


//***************************/
// Default constructor
Employee::Employee()
{
	string name = " ";
	double currentSalary = 00000;
	double taxRate = 0.00;
}

//***************************/
// Destructor
Employee::~Employee()
{
}


/****************************/
// define set method to save data into member variables
void Employee::setEmployeeData(string n, double cs , double tr)
{
	
	 n = name;
	 cs = currentSalary;
	 tr = taxRate;

	idNumber++;
}


/****************************/
// define print method to display employee data 
void Employee::print()
{
	cout << name << "(" << idNumber << ")" << " $" << currentSalary << endl;
}


/****************************/
// define method to give employees a raise
void Employee::payRaise(double salaryWithRaise)
{
	double raise;
	salaryWithRaise = raise + currentSalary;
}

/****************************/
// define method to calculate employees taxes paid amount
double Employee::taxesPaid(double s)
{
	s = currentSalary * taxRate;
	return s;
}

/****************************/
// define static method to return static member variable value
int Employee::idNumberCount()
{
	
	return idNumber;
}
