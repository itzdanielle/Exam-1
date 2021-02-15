# Exam-1
#include <iomanip>
#include <iostream>
using namespace std;

int main() {
	cout << setprecision(2) << fixed;

	double num1;
	double num2;
	double mean;
	double average;

	cout << "This program finds the average and" << endl;
	cout << "mean of 2 square numbers" << endl;
	cout << "Input the first number:\n";
	cin >> num1;
	cout << "Input the second number:\n";
	cin >> num2;
	average = (num1 + num2) / 2;
	cout << "The average is " << average << endl;
	mean = ((num1 * num1) + (num2 * num2)) / 2;
	cout << "The mean average is " << mean << endl;
}
