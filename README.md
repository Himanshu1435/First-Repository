#include<iostream.h>
#include<conio.h>

class fact
{
int n ;
long a ;
  public:
  void input ()
  {
  cout <<"Enter a number";
  cin>>n;
  }
  void fact1()
  {
  a=1;
  for (int i=1; i<=n;i++)
  a=a*i;
  }
  void output()
  {
  cout<<"factorial is"<<a;
  }
  };


  void main()
  {
  fact x ;
  x.input ();
  x.fact1();
  x.output();
  }
