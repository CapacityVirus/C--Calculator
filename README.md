C--Calculator
=============
#include <iostream>

using namespace std;


class calculator
{

private:
	int x;
	int y;
	int z;
	int sum;

public:
	calculator(int x, int y, int z);
	

	calculator::calculator()
	{
		x = x;
		y = y;
		z = z;
	}
	void setValue(int x, int y, int z)
	{
		x = x;
		y = y;
		z = z;

	}
	int funcOperator()
	{
		if (z == 1)
		{
			return (x + y);
		}
		if (z == 2)
		{
			return (x - y);
		}
		if (z == 3)
		{
			return (x * y);
		}
		if (z == 4)
		{
			return (x / y);
		}
		

	}

};

int main()
{
	calculator cal;
	cal.setValue(5, 7, 1);
	cout << cal.funcOperator() << endl;
	system("pause");
	return 0;
}


}
C++ Calculator
