# Take 10 integer inputs from user and store them in an array. Now, copy all the elements in another array but in reverse order.

#include<iostream>
using namespace std;
  
void main()
{

	int arr1[10];
	int arr2[10];
	for (int i = 0; i < 10; i++)
	{
		cout << "Enter value : "; cin >> arr1[i];
	}
	for (int i = 0; i < 10; i++)
	{
		arr2[9 - i] = arr1[i];                          //at 9th position of arr2, the element stored will be element 1 of arr1
	}
	cout << "Array 1 " << "  " << "Array 2" << endl;
	for (int i = 0; i < 10; i++)
	{
		cout << arr1[i] <<"  "<<arr2[i]<<endl;
	}
	system("pause");
  
 }
