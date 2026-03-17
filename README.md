# DS-LAB
                                                                week 1  
1.Write a c++ program to display name,rollno.,branch and section by using cout
program : 
#include<iostream>
int main()
{
std :: cout<<"A.L.V.SAI.MONISHA";
std :: cout<<"25A31A05IX";
std :: cout<<"CSE";
std :: cout<<"F";
return 0;
}

2.Write a C++ program to identify biggest value among given three values
Program:
#include<iostream>
using namespace std;
int main(){
int a,b,c;
cout<<"enter any 3 numbers";
cin>>a>>b>>c;
if((a>b)&&(a>c))
cout<<("a is big");
else if(b>c)
cout<<("b is big");
else
cout<<("c is big");
return 0;
}

3.Write a C++ program to indentify whether the given number is leap year or not
Program:
#include<iostream>
using namespace std;
int main()
{
int n;
cout<<"enter a year";
cin>>n;
if(n%4==0&& n%100==0//n%400==0)
cout<<"leap year";
else
cout<<"not a leap year";
return 0;
}

4.Write a c++ program to calculate Factorial of a given number.
PROGRAM
#include <iostream>
using namespace std;
int main(){
int n,fact=1;
cout << "enter in value";
Cin>>n;n=3
if (n==0)
Cout<<fact;
else
for (int i=1; i<=n; i++)
fact = fact*1;
cout << "factorial value is "<< fact;
return 0;
OUTPUT
Enter n value 5
Factorial value-120

5.Write a c++ program to decide whether the given number is prime or not.
PROGRAM:
#include <iostream> 
using namespace std; 
int main()
{
intn, count=0; 
cout <<"enter n'value";
Cin>>n; 
for (int i=1; i<=n; i++) { 
if (n%i==0) count = count+1; 
if (count=-2) count <<n<<< " is prime number;
else
count<< n<< "is not prime number; 
return 0;
}
OUTPUT
Enter n value - 5
5 is prime number

                                                      week 2
1.Write a c++ program to read 1D array elements and print the same
PROGRAM:
#include <iostream>
using namespace std;
int main()
{
    int a[10], i;
 cout << "Enter array elements:\n";
    for(i = 0; i < 10; i++)
    {
        cin >> a[i];
    }
cout << "\nArray elements are:\n";
    for(i = 0; i < 10; i++)
    {
        cout << a[i] << " ";
    }
 return 0;
}
OUTPUT
Enter array elements:
12 34 55 67 18 19 20 22 23 28

Array elements are:
12 34 55 67 18 19 20 22 23 28

2.Write a c++ program to read 1D array elemtns using pointers
PROGRAM:
#include <iostream>
using namespace std;

int main()
{
    int a[10], i;
    int *p = a;
cout << "Enter array elements:\n";
    for(i = 0; i < 10; i++)
        cin >> *(p + i);
cout << "\nArray elements are:\n";
    for(i = 0; i < 10; i++)
        cout << *(p + i) << " ";
  return 0;
}
OUTPUT
Enter array elements:
1 2 3 4 5 6 7 8 9 10

Array elements are:
1 2 3 4 5 6 7 8 9 10

3.Write a c++ program to read,display 1D array elements using DMA
PROGRAM:
#include <iostream>
using namespace std;

int main()
{
    int *a, n, i;
cout << "Enter number of elements: ";
    cin >> n;
a = new int[n];
cout << "Enter array elements:\n";
    for(i = 0; i < n; i++)
        cin >> a[i];
cout << "\nArray elements are:\n";
    for(i = 0; i < n; i++)
        cout << a[i] << " ";
 delete[] a;
    return 0;
}
OUTPUT:
Enter number of elements: 5
Enter array elements:
10 20 30 40 50

Array elements are:
10 20 30 40 50

4.Write a c++ program to swap two numbers by using referencing
PROGRAM:
#include <iostream>
using namespace std;

void swap(int &x, int &y)
{
    int temp;
    temp = x;
    x = y;
    y = temp;
}
int main()
{
    int a, b;
 cout << "Enter two numbers: ";
    cin >> a >> b;
 swap(a, b);
cout << "After swapping:\n";
    cout << "a = " << a << " b = " << b;
return 0;
}
OUTPUT:
Enter two numbers: 5 10
After swapping:
a = 10 b = 5

5.Write a c++ program to implement function overloading
PROGRAM:
#include <iostream>
using namespace std;

int add(int a, int b)
{
    return a + b;
}

float add(float a, float b)
{
    return a + b;
}

int main()
{
    cout << "Sum of integers: " << add(5, 10) << endl;
    cout << "Sum of floats: " << add(2.5f, 3.5f);
return 0;
}
OUTPUT:
Sum of integers: 15
Sum of floats: 6

week 3
