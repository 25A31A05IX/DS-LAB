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
1.Write a c++ program to demonstrate class and object
PROGRAM:
#include <iostream>
using namespace std;

class student {
public:
    int no, mark; // data members
void read() { // member function-1
        cout << "enter rno and marks: ";
        cin >> no >> mark;
    }
 void display() { // member function-2
        cout << "rno is: " << no << endl;
        cout << "mark is: " << mark << endl;
    }
};
int main() {
    student s1;      // Create object
    s1.read();       // Call read function
    s1.display();    // Call display function
    return 0;
}
OUTPUT:
Enter r no. - 2
marks-50
rno is: 2
marks is : 50

2.Write a c++ code to demonstrate destructor and constructor
PROGRAM:
#include <iostream>
using namespace std;

class Calculator
{
public:
    int a, b;
  void input()
    {
        cout << "Enter two numbers: ";
        cin >> a >> b;
    }
void add()
    {
        cout << "Addition = " << a + b << endl;
    }
void subtract()
    {
        cout << "Subtraction = " << a - b << endl;
    }
 void multiply()
    {
        cout << "Multiplication = " << a * b << endl;
    }
    void divide()
    {
        cout << "Division = " << a / b << endl;
    }
};
int main()
{
    Calculator c;
    c.input();
    c.add();
    c.subtract();
    c.multiply();
    c.divide();
 return 0;
}
OUTPUT:
Constructor is called
Destructor is called


3. Question: Write a C++ program to implement linear search.

Program:
#include <iostream>
using namespace std;

int main()
{
    int a[10], key, i;
    cout << "Enter 10 elements:\n";
    for(i = 0; i < 10; i++)
        cin >> a[i];

  cout << "Enter element to search: ";
    cin >> key;
 for(i = 0; i < 10; i++)
    {
        if(a[i] == key)
        {
            cout << "Element found at position " << i + 1;
            return 0;
        }
    }
 cout << "Element not found";
    return 0;
}
Output:
Enter 10 elements:
1 2 3 4 5 6 7 8 9 10
Enter element to search: 5
Element found at position 5


4. Question: Write a C++ program to calculate number of occurrences of a search key using linear search.
Program:
#include <iostream>
using namespace std;

int main()
{
    int a[10], key, i, count = 0;
cout << "Enter 10 elements:\n";
    for(i = 0; i < 10; i++)
        cin >> a[i];
cout << "Enter element to search: ";
    cin >> key;
for(i = 0; i < 10; i++)
    {
        if(a[i] == key)
            count++;
    }
 cout << "Number of occurrences = " << count;
    return 0;
}
Output:
Enter 10 elements:
1 2 3 2 4 2 5 2 6 2
Enter element to search: 2
Number of occurrences = 5


5. Question: Write a C++ program to implement binary search.
Program:
#include <iostream>
using namespace std;

int main()
{
    int a[10], key;
    int low = 0, high = 9, mid;
cout << "Enter 10 sorted elements:\n";
    for(int i = 0; i < 10; i++)
        cin >> a[i];
cout << "Enter element to search: ";
    cin >> key;
while(low <= high)
    {
        mid = (low + high) / 2;
if(a[mid] == key)
        {
            cout << "Element found at position " << mid + 1;
            return 0;
        }
        else if(a[mid] < key)
            low = mid + 1;
        else
            high = mid - 1;
    }
 cout << "Element not found";
    return 0;
}
Output:
Enter 10 sorted elements:
1 2 3 4 5 6 7 8 9 10
Enter element to search: 7
Element found at position 7

                                                     week 4
1. Question: Write a C++ program to implement Selection Sort.
Program:
#include <iostream>
using namespace std;

int main()
{
    int a[10], i, j, min, temp;
cout << "Enter 10 elements:\n";
    for(i = 0; i < 10; i++)
        cin >> a[i];
for(i = 0; i < 9; i++)
    {
        min = i;
        for(j = i + 1; j < 10; j++)
        {
            if(a[j] < a[min])
                min = j;
        }
        temp = a[i];
        a[i] = a[min];
        a[min] = temp;
    }
 cout << "Sorted array:\n";
    for(i = 0; i < 10; i++)
        cout << a[i] << " ";
return 0;
}
Output:
Enter 10 elements:
64 25 12 22 11 90 45 33 10 5
Sorted array:
5 10 11 12 22 25 33 45 64 90


2. Question: Write a C++ program to implement Insertion Sort.

Program:
#include <iostream>
using namespace std;
int main()
{
    int a[10], i, j, key;
cout << "Enter 10 elements:\n";
    for(i = 0; i < 10; i++)
        cin >> a[i];
for(i = 1; i < 10; i++)
    {
        key = a[i];
        j = i - 1;
while(j >= 0 && a[j] > key)
        {
            a[j + 1] = a[j];
            j--;
        }
        a[j + 1] = key;
    }
 cout << "Sorted array:\n";
    for(i = 0; i < 10; i++)
        cout << a[i] << " ";
 return 0;
}
Output:
Enter 10 elements:
9 5 1 4 3 8 2 7 6 0
Sorted array:
0 1 2 3 4 5 6 7 8 9


3. Question: Write a C++ program to implement Bubble Sort.

Program:
#include <iostream>
using namespace std;

int main()
{
    int a[10], i, j, temp;
 cout << "Enter 10 elements:\n";
    for(i = 0; i < 10; i++)
        cin >> a[i];
for(i = 0; i < 9; i++)
    {
        for(j = 0; j < 9 - i; j++)
        {
            if(a[j] > a[j + 1])
            {
                temp = a[j];
                a[j] = a[j + 1];
                a[j + 1] = temp;
            }
        }
    }
cout << "Sorted array:\n";
    for(i = 0; i < 10; i++)
        cout << a[i] << " ";
  return 0;
}
Output:
Enter 10 elements:
5 3 8 4 2 7 1 10 6 9
Sorted array:
1 2 3 4 5 6 7 8 9 10

                                                 week 5
1. Question: Write a C++ program to perform addition of n elements using dynamic memory allocation.
Program:
#include <iostream>
using namespace std;

int main()
{
    int *a, n, i, sum = 0;
cout << "Enter number of elements: ";
    cin >> n;
 a = new int[n];
 cout << "Enter elements:\n";
    for(i = 0; i < n; i++)
    {
        cin >> a[i];
        sum += a[i];
    }
 cout << "Sum of elements = " << sum;
 delete[] a;
    return 0;
}
Output:
Enter number of elements: 5
Enter elements:
10 20 30 40 50
Sum of elements = 150


2. Question: Write a C++ program to create four nodes in a single linked list using dynamic memory allocation.
Program:
#include <iostream>
using namespace std;

struct Node
{
    int data;
    Node* next;
};

int main()
{
    Node *head, *second, *third, *fourth;
  head = new Node();
    second = new Node();
    third = new Node();
    fourth = new Node();
 head->data = 10;
    head->next = second;
second->data = 20;
    second->next = third;
third->data = 30;
    third->next = fourth;
fourth->data = 40;
    fourth->next = NULL;
 Node* temp = head;
    cout << "Linked List:\n";
    while(temp != NULL)
    {
        cout << temp->data << " -> ";
        temp = temp->next;
    }
    cout << "NULL";
return 0;
}
Output:
Linked List:
10 -> 20 -> 30 -> 40 -> NULL


3. Question: Write a C++ program to create single linked list nodes based on user input using dynamic memory allocation.
Program:
#include <iostream>
using namespace std;

struct Node
{
    int data;
    Node* next;
};

int main()
{
    Node *head = NULL, *temp, *newNode;
    int n, i;
cout << "Enter number of nodes: ";
    cin >> n;
for(i = 0; i < n; i++)
    {
        newNode = new Node();
        cout << "Enter data: ";
        cin >> newNode->data;
        newNode->next = NULL;
 if(head == NULL)
        {
            head = temp = newNode;
        }
        else
        {
            temp->next = newNode;
            temp = newNode;
        }
    }
cout << "Linked List:\n";
    temp = head;
    while(temp != NULL)
    {
        cout << temp->data << " -> ";
        temp = temp->next;
    }
    cout << "NULL";
return 0;
}

Output:
Enter number of nodes: 3
Enter data: 5
Enter data: 10
Enter data: 15
Linked List:
5 -> 10 -> 15 -> NULL
