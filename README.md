# #include<iostream>
using namespace std;

int main()
{
	int age;
	cout<<"enter your age:";
	cin>>age;
	if (age<18){
		cout<<"Hey buddy!! you still have to wait "<<18-age<<" years to cast your vote";
	}
	else{
		cout<<"You are eligible to cast your vote";
		
	}
	return 0;
	}
