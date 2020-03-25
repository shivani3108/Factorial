# Factorial

//Factorial of a number using iterative approach
#include<iostream> 
using namespace std; 
int factorial(unsigned int n);   // Function to find factorial of given number 
int main() 
{ 
    int num; 
    cout<<"Program to find factorial of a number"<<endl;
    cout<<"Enter the number whose factorial you want to know: ";
    cin>>num;
    cout<<"Factorial of "<<num <<" is: " <<factorial(num)<<endl; 
    return 0; 
}    
unsigned int factorial(unsigned int n) 
{ 
    if (n == 0) 
    return 1; 
    else
    return (n * factorial(n - 1)); 
} 
  
