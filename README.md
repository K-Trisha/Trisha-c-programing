//palindrome number


#include <iostream>   
using namespace std;   
int main() 
{       
	string s;       
	cin>>s;       
	string rev ;       
	for(int i=0;i<s.size();i++)
	{           
		rev=s[i]+rev;       
	}       
	if (s==rev)
	{          
		 cout<<"YES";      
	}       
	else
	{   
		 cout<<"NO";       
	}   
}	
