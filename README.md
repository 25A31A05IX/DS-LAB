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

4.Write a C++ program to calculate factorial of given number
Program:
#include <iostream>
using namespace std;
int main()
{
int n,fact=1;
cout<<"
