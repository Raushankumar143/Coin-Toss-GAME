# Coin-Toss-GAME
Coin in two permeability the HEAD &amp; TALL, So the coin is tosses then to get Head or Tall.

#include<iostream>
#include<stdlib.h>
using namespace std;
int main()
{
    int c;
cout<<"Welcome To Coin Toss GAME."<<endl;
while(1){
        cout<<"1.START..."<<endl;
        cout<<"2.Quit..."<<endl;
        cin>>c;
        switch(c){
            case 1:
                if(rand()%2==0)
                 {
                    cout<<"HEAD"<<endl;
                  }else{
                     cout<<"TALL"<<endl;
                }
            case 2: exit(0);
            default: cout<<"invalid input!"<<endl;
        }
}
cout<<"Thank You";
return 0;
}
