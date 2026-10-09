# Daily-expenese
#include <iostream>

using namespace std;

int main(){
	string name; 
    int breakfast, lunch, dinner, total;
	
	cout<<"Please input your name:";
	cin>>name;
	cout<<"Please input the amount spent on breakfast:";
	cin>>breakfast;
	cout<<"Please input the amount spent on lunch:";
	cin>>lunch;
	cout<<"Please input the amount spent on dinner:";
	cin>>dinner;
	
	total=breakfast+lunch+dinner;

	cout<<"================\n";
	
	cout<<"Name :"<<name<<endl;
	cout<<"Your spent today "<<total <<endl;
	
	if (total>=10000){
		cout<<"your should not spend more then 10000 Riel on this day ";
	}
	else if (total<=9999 && total>=5000){
		cout<<"Your normal today";
	}
	else if(total<=4999){
		cout<<"Your so good today";
	}
	
		
		
 
	return 0;
}
