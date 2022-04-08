# Vriti31
#include <iostream>
using namespace std;
int main()
{
int arr[10], i, num, index;
cout << "Enter 20 Numbers: ";
for (i = 0; i < 20; i++)
cin >> arr[i];
cout << "Enter a Number to Search: ";
cin >> num;
for (i = 0; i < 20; i++)
{
if (arr[i] == num)
{
index = i;
break;
}
}
cout << "Found at Index No." << index;
cout << endl;
return 0;
}
