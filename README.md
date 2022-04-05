# Pixer

#include <iostream>
#include <math.h>
using namespace std;

template<class T>
T Max(T a, T b){
	return a>b? a:b; 
}


int main () {
	int a=4, b=7;
	cout<<Max(a,b)<<endl;
	
	double c=4.2, d=4.7;
	cout<<Max(c,d)<<endl;
	
	string e="salom", f="dunyo";
	cout<<Max(e,f)<<endl;
	
	cout<<Max<double>(a,d)<<endl;
}
