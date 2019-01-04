# Uri-Online-Judge-1043-cpp

#include<iostream>
#include<stdio.h>
using namespace std;
int main()
{
    float a,b,c;



    while(cin>>a>>b>>c)
    {
    if((a+b) >c || (b+c) >a || (c+a) >b)
        cout<<"Perimetro = "<<a+b+c<<endl;
    else
        cout<<"Area"<<(a+b)*c/2.0<<endl;
    }

        return 0;
}
