#include <iostream>
#include <Windows.h>
using namespace std;
int main()
{
SetConsoleCP(1251);
SetConsoleOutputCP(1251);
double a, b, c;
cout << "Введіть три від'ємні числа: ";
cin >> a >> b >> c;
double max_val;
if (a > b && a > c) {
max_val = a;
}
else if (b > c) {
max_val = b;
}
else {
max_val = c;
}
double cube = max_val * max_val * max_val;
cout << "Найбільше число: " << max_val << endl;
cout << "Куб цього числа: " << cube << endl;
return 0;
}
