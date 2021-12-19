# lecture-6

name that shape
#include<iostream>
using namespace std;
int main()
{
	double side;
	cout << "Enter the sides number to see the shape name (minimum 3 sides, maximum 10) \n";
	cin >> side;
	
	if (side <= 2)
	{
		cout << "You enter 2 as side, which is incorrect input";
	}
	else if (side==3) 
	{
		cout << "Triangle  has " << side << " sides" << endl;
	}
	else if (side == 4)
	{
		cout << "Square | Rectangle has " << side << " sides" << endl;
	}
	else if (side == 5)
	{
		cout << "Pentagon has " << side << " sides" << endl;
	}
	else if (side == 6)
	{
		cout << "Hexagon have " << side << " sides" << endl;

	}
	else if (side == 7)
	{
		cout << "Hepaton have " << side << " sides" << endl;

	}
	else if (side == 8)
	{
		cout << "Octagon have " << side << " sides" << endl;

	}

	else if (side == 9)
	{
		cout << "Nonagon have " << side << " sides" << endl;

	}
	else if (side == 10)
	{
		cout << "Decagon have " << side << " sides" << endl;

	}
	else 
	{
		cout << "Incorrect";

	}

	return 0;
}
            
            
            profit or loss
#include<iostream>
using namespace std;
int main()
{
	double Purchase, sale, x;
	cout << "Enter the purchase price: \n";
	cin >> Purchase;
	cout << "\nEnter the sale price: ";
	cin >> sale;
	x = sale - Purchase; 
	if (x > 0) 
	{
		cout << "You have a Profit of " << x << endl;
	}
	else if (x < 0) // For loss
	{
		cout << "You had a Loss of " << x << endl;
	}
	else if(x==0)
	{
		cout << "No loss no profit." << endl;
	}
	else
	{
		cout << "Incorrect input";
	}
	return 0;
}
            Number checker positive or not
            
#include <iostream>
using namespace std;

int main()
{
    cout << "Enter the number to see whether its positive, negative or zero\n";
    double number;
    cin >> number;
    if (number == 0)
    {
        cout << "The number you entered is zero";
    }

    else  if (number > 0)
    {
        cout << "The number you entered is positive";
    }
    else  if (number < 0)
    {
        cout << "The number you entered is negative";
    }
    else
    {
        cout << "Incorrect input";
    }
}
                
                
                
                even ODD
                #include <iostream>
using namespace std;
int main()
{
    cout << "Enter the number to see whether its even or odd\n";
    int number;
    cin >> number;
    if (number % 2 == 0)
    {
        cout << "\nThe entered number is Even\n";
    }
    else if (number % 2 != 0)
    {
        cout << "The number entered is odd";
    }
    else
    {
        cout << "Incorrect";
    }
}
  
  vote
  #include <iostream>
using namespace std;

int main()
{
    cout << "Kindly enter your age to see whether you can vote or not!\n";
    int age;
    cin >> age;
    if(age>=18)
    {
        cout << "You can vote";

    }
    else
    {
        cout << "Sorry not today";
    }
  
}
  
 Good morning
  
  // am.pm.cpp : This file contains the 'main' function. Program execution begins and ends there.
//

#include<iostream>
using namespace std;
int main()
{
	cout << "Enter the time in 24 hour pattern to see whether it Morning, Afternoon, Evening or Night\n";
	double time;
	cin >> time;
	if (time < 12)
	{
		cout << "Good Morning";
	}
	else if (time >= 12 && time < 18)
	{
		cout << "Good Afternoon";
		}
	else if (time >=18 && time < 21)
	{
		cout << "Good Evening";
	}
	else if (time >=21 && time <24)
	{
		cout << "Good Night";
	}
	else
	{
		cout << "Incorrect input";
	}
}
            
