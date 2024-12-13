# array-getting-input-from-user
#include <iostream>
using namespace std;

int main() {
     int numbers[8];
     cout<<"enter numbers 8";
     
     for(int i=0;i<8;i++){
         cin>>numbers[i];
     }
     for(int i=0;i<8;i++){
     cout<<numbers[i];
     }

    return 0;
}
