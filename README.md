mihanshu
========
#include<iostream>
using namespace std;
double micifang(double a,int b)
{
 
if(b==0)
   return 1;

return (micifang(a,b-1 )*a);
  
}
int main()
{
double a;int b;
cout<<"Input a b:"<<endl;
cin>>a>>b;
 
cout<<micifang(a,b)<<endl;
 system("pause");
 return 0;
}
