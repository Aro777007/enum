#include <iostream>
using namespace std;
#include <string>

enum color
{
	red,
	blue,
	green,
	black,
	white,
	brown,
	purple,
};


string convertor(color c)
{
	switch (c) {
	case red:
		return "red";
	case blue:
		return "blue";
	case green:
		return "green";
	case black:
		return "black";
	case white:
		return "white";
	case brown:
		return "brown";
	case purple:
		return"purple";
	default:
		return "miban";
	}


}


int main()
{	
	color c;
	c = red;
	for (int i = red; i <= purple; ++i)
	{
		string cr = convertor(color(i));
		cout << cr << endl; ;
	}
}




