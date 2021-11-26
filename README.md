# Some-counting
#For loop
#include<iostream>
using namespace std;
int main()
{
	cout << "The values from 0 to 50 are: " << endl;
	for (int i = 0; i <= 50; i++)
	{
		cout << i << " " << endl;
	}

	cout << "\nThe values from 50 to 0 are: " << endl;
	for (int j = 50; j >= 0; j--)
	{
		cout << j << " "<<endl;
	}

	cout << "\nThe values from 30 to 50 are: " << endl;
	for (int k = 30; k <= 50; k++)
	{
		cout << k << " " << endl;
	}

	cout << "\nThe values from 50 to 10 with decrements of 2 are: " << endl;
	for (int x = 50; x >= 10; x = x - 2)
	{
		cout << x << " " << endl;
	}

	cout << "\nThe values from 100 to 200 with increment of 5 are: " << endl;
	for (int y = 100; y <= 200; y = y + 5)
	{
		cout << y << " " << endl;
	}
	return 0;
}
