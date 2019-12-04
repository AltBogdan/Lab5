# Lab5
LabWork
#include "windows.h"
#include "iostream"
#include "math.h"

using namespace std;

int main()
{
	double a, x, y, z;
	cin >> x >> y >> z;
	if (pow(x, 2) + y > 0 && x + sin(13)!=0)
	{
		a = sqrt(pow(x, 2) + y) - pow(y, 2) * pow(sin(x + z), 3) / (x + sin(13));
		cout << a << endl;
	}
	else
	{
		cout << "error";
	}
	system ("pause");
	return 0;
}
