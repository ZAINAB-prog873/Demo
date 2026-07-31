# Demo
This is my first git repository.
<br>
#include <iostream>
using namespace std;
double calculator(double x , double y , int c){
    if(c == 1) return x+y ;
    else if (c == 2) return x-y ;
    else if (c == 3) return x*y ;
    else if (c == 4) return x/y ;
    else {
        cout<<"Invalid choice ! "<<endl;
    }
    return 0.0 ;
}
int main() {
    double x , y ;
    double output ;
    cout<<"CALCULATOR OPTIONS "<<endl;
    cout<<"1) Addition "<<endl;
    cout<<"2) Subtraction "<<endl;
    cout<<"3) Multiplication "<<endl;
    cout<<"4) Division "<<endl;
    int c ;
    cout<<"Enter yout choise (1,2,3,4) : " ;
    cin>>c;
    cout<<"Enter the values to be calculated : "<<endl;
    cout<<" 1st value : ";
    cin>>x;
    cout<<" 2nd value : ";
    cin>>y;
    cout<<"Output = "<< calculator(x , y , c) <<endl; 
    return 0;
}
