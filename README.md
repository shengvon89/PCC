PCC
===

//Question 1
# include <iostream>
#include <sstream>

using namespace std;

int main()
{
  string num[100];
	int number = 1;
	for(int i=0; i<100; i++)
	{
		if (number%3 == 0 && number%5 == 0)
		{
			num[i] = "AaaBbb";
		}
		else if(number%3 == 0)
		{
			num[i] = "Aaa";
		}
		else if(number%5 == 0)
		{
			num[i] = "Bbb";
		}
		else
		{
			std::string s;  
			std::stringstream out;  
			out << number;
			s = out.str();
			num[i] = s;
		}
		number ++;
		cout << num[i] << endl;	
	}
	system ("pause");
}

//Question 2
//bool isPalindrome(int x) {
//  change the int to string
//  split the string. ie: 1001->1,0,0,1 and put into arraylist
//  get the size of array. ie: 4
//  compare the 1st and last, 2nd wif 2nd last. ie: array[0] == array[3], array[1] == array[2]
//  if both true then return true. else return false
//}

//Queistion 3
//class Mamalia
//{
//	string gotleg;
//	string noleg;
//	string liveinwater;
//	string canfly;
//	string liveatland;
//}

Read it..^^
