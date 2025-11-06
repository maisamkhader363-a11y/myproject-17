#include<iostream>
using namespace std;
int main()
{
	cout << "plz enter a number" << endl;
	int num = 0;
	cin >> num;
	if (num < 1)
	{
		cout << "invalid input" << endl;
	}
	else
	{
		for (int i = num; i >= 1; i--)
			cout << i << " ";
		return 0;
	}

}
