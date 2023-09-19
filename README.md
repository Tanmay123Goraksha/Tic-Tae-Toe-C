# Tic-Tae-Toe-C
#include<iostream>
using namespace std;
int main(){
	
	int choice;
	char c[3][3]={{1,2,3},{4,5,6},{7,8,9,}};
	cout<<"tic tac toe game\n\n";
	cout<<"\n";
	cout<<"Get Ready Player1[X] Player2[0]\n";
	cout<<"\n";
	cout<<"\n";
	cout<<"\n";
cout<<"\t\t   |               |               |               |\n";
cout<<"\t\t   | "<<c[0][0]<<" | "<<c[0][1]<<" |"<<c[0][2]<<"  |\n";
cout<<"\t\t __|__             |__             |__             |__\n";
cout<<"\t\t   | "<<c[1][0]<<" | "<<c[1][1]<<" | "<<c[1][2]<<" |\n";
cout<<"\t\t __|__             |__             |__             |__\n";
cout<<"\t\t   | "<<c[2][0]<<" |  "<<c[2][1]<<"|  "<<c[2][2]<<"|\n";
cout<<"\t\t   |               |               |               |\n";
cout<<"\t\t   |               |               |               |\n";

while(1){
	cout<<"playerX[X] turn:\n";
	cout<<"choose position\n";
	cin>>choice;
	switch(choice){
		case 1:
			c[0][0]='X';
			break;
			case 2:
			c[0][1]='X';
			break;
			case 3:
			c[0][2]='X';
			break;
			case 4:
			c[1][0]='X';
			break;
			case 5:
			c[1][1]='X';
			break;
			case 6:
			c[1][2]='X';
			break;
			case 7:
			c[2][0]='X';
			break;
			case 8:
			c[2][1]='X';
			break;
			case 9:
			c[2][2]='X';
			break;
			default:
				cout<<"invalid character";
				break;
			
	}
	

cout<<"\t\t   |  |  |  |\n";
cout<<"\t\t   | "<<c[0][0]<<" | "<<c[0][1]<<" |"<<c[0][2]<<"  |\n";
cout<<"\t\t __|__|__|__|__\n";
cout<<"\t\t   | "<<c[1][0]<<" | "<<c[1][1]<<" | "<<c[1][2]<<" |\n";
cout<<"\t\t __|__|__|__|__\n";
cout<<"\t\t   | "<<c[2][0]<<"|  "<<c[2][1]<<"|  "<<c[2][2]<<"|\n";
cout<<"\t\t   |  |  |  |\n";
cout<<"\t\t   |  |  |  |\n";
if  ((c[0][0]=='X'&& c[0][1]=='X'&& c[0][2]=='X')||
     (c[1][0]=='X'&& c[1][1]=='X'&& c[1][2]=='X')||
	 (c[2][0]=='X'&& c[2][1]=='X'&& c[2][2]=='X')||
	 (c[2][0]=='X'&& c[2][1]=='X'&& c[2][2]=='X')||
	 (c[0][0]=='X'&& c[1][1]=='X'&& c[2][2]=='X')||
	 (c[2][0]=='X'&& c[1][1]=='X'&& c[0][2]=='X')||
	 (c[0][0]=='X'&& c[1][0]=='X'&& c[2][0]=='X')||
	 (c[0][1]=='X'&& c[1][1]=='X'&& c[2][1]=='X')||
	 (c[0][2]=='X'&& c[1][2]=='X'&& c[2][2]=='X')
	 
	 ){
	 	cout<<"X Won";
	 	exit(0);
	 }
		 
		 
		 
		 cout<<"player1[0] turn";
		 cin>>choice;
		 switch(choice){
		 	case 1:
			c[0][0]='0';
			break;
			case 2:
			c[0][1]='0';
			break;
			case 3:
			c[0][2]='0';
			break;
			case 4:
			c[1][0]='0';
			break;
			case 5:
			c[1][1]='0';
			break;
			case 6:
			c[1][2]='0';
			break;
			case 7:
			c[2][0]='0';
			break;
			case 8:
			c[2][1]='0';
			break;
			case 9:
			c[2][2]='0';
			break;
			default:
				cout<<"invalid character";
				break;
		 	
		 }
		 cout<<"\t\t   |  |  |  |\n";
cout<<"\t\t   | "<<c[0][0]<<" | "<<c[0][1]<<" |"<<c[0][2]<<"  |\n";
cout<<"\t\t __|__|__|__|__\n";
cout<<"\t\t   | "<<c[1][0]<<" | "<<c[1][1]<<" | "<<c[1][2]<<" |\n";
cout<<"\t\t __|__|__|__|__\n";
cout<<"\t\t   | "<<c[2][0]<<"|  "<<c[2][1]<<"|  "<<c[2][2]<<"|\n";
cout<<"\t\t   |  |  |  |\n";
cout<<"\t\t   |  |  |  |\n";
}
if  ((c[0][0]=='0'&& c[0][1]=='0'&& c[0][2]=='0')||
     (c[1][0]=='0'&& c[1][1]=='0'&& c[1][2]=='0')||
	 (c[2][0]=='0'&& c[2][1]=='0'&& c[2][2]=='0')||
	 (c[2][0]=='0'&& c[2][1]=='0'&& c[2][2]=='0')||
	 (c[0][0]=='0'&& c[1][1]=='0'&& c[2][2]=='0')||
	 (c[2][0]=='0'&& c[1][1]=='0'&& c[0][2]=='0')||
	 (c[0][0]=='0'&& c[1][0]=='0'&& c[2][0]=='0')||
	 (c[0][1]=='0'&& c[1][1]=='0'&& c[2][1]=='0')||
	 (c[0][2]=='0'&& c[1][2]=='0'&& c[2][2]=='0')
	 
	 ){
	 	cout<<"0 Won";
	  exit(0);
		 }
		 return 0;
	}
		 
		 
		 
		 
		 
