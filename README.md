complementi
===========

complemetni matematica
#include<iostream>
using namespace std;
int y;
int funz(int x1)
{
     y=x1+2;
     return y;
}
 int main()
{
   int y1,y2;
   int a,b;
   cin>>a;
   cin>>b;
   funz(a);
   y1=y;
   funz (b);
   y2=y;
   if((y1>0 && y2<0) || (y1<0 && y2>0))
   {
    cout<<"la funzione contiene uno 0";
   }
   else
   {
       cout<<"la funzione in questi due valori non ha zeri";
   }
system("pause");
return 0;
}
