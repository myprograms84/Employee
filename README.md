# Employee

#pragma once //include to prevent redefining
#include <iostream>
#include <string>

using namespace std;

//declare Employee class
class Employee
{
private: // declare private member variables

	string name;
	double currentSalary;
	double taxRate;

	// declare private static member variables
	static int idNumber;


public:
	Employee(); //default constructor
	~Employee(); //deconstructor


   /****************************/
   // declare set method to save data into member variables
	void setEmployeeData(string, double, double);


	/****************************/
	// declare print method to display employee data 
	void print();


	/****************************/
	// declare incremental method to give employees a raise
	void payRaise(double);

	/****************************/
	// declare taxesPaid method to calculate and return total taxes paid (calculate salary * tax rate)
	double taxesPaid(double s);

	/****************************/
	// declare static method to access static member
	static int idNumberCount();

};
