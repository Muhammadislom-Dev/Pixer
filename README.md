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

	

template <class T>
class nuqta {
	public:
		T x;
		T y;
		
		nuqta (){}
		nuqta (T x, T y):x(x),y(y){
		}
};

int main () {
	nuqta <int>a(5,7);
	nuqta <double>b(7.8,6.9);
	
	cout<<a.x<<" "<<a.y<<endl;
	cout<<b.x<<" "<<b.y<<endl;
}
