# startup-repository
#include<iostream>
#include<cmath>
#include<clocale>
using namespace std;
int main() {
	setlocale( LC_ALL, "Russian");
	double a, z1, z2;
	cout << endl << "Введите число ";
	cin >> a;
	z1 = (sin(3.14 / 2 + 3 * a)) / (1 - sin(3 * a - 3.14));
	z2 = 1 / tan( (5 * 3.14) / 4 + 3 * a/ 2 );
	cout << endl << "Результат вычисления по формулам: " << endl;
	cout << endl <<"z1= " << z1 << "  " <<"z2= "<< z2 << endl;
	return 0;
}
