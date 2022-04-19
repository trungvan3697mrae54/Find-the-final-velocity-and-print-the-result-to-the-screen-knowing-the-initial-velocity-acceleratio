# Find-the-final-velocity-and-print-the-result-to-the-screen-knowing-the-initial-velocity-acceleratio
Suppose a car has an initial velocity v0, an acceleration a and a time t. Write a C++ program to find the final speed of the car and print the result to the screen.
#include <iostream>
#include <conio.h>
using namespace std;
int main()
{

int v,u,a,t;
cout << "Tap toc v0, gain a, time t: " << endl;
cin>>u>>a>>t;
v=u+a*t;
cout << "The final valve is " << v << "." << endl;
return 0;
}
