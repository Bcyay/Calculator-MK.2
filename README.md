# Calculator-MK.2
My 2nd Calculator.



#include <iostream>
#include <cmath>
#include <cstdlib>
#include <ctime>
using namespace std;

int main()
{
   int a;
   string mode;
   int b;
   int sm;
   
   
   cout<<"NUMBERS NOWWWW!!!"<<endl;
   cout<<"Example: 1 + 2"<<endl;
   cin>> a >> mode >> b;
   
   cout<< "a is "<<a<<", mode is "<<mode<<", b is "<<b<<endl;
   
  
  if(mode=="+") 
  {
      sm= a + b;
  }
  
  if(mode=="*")
  {
      sm= a * b;
  }
  
  if(mode=="-")
  {
      sm= a - b;
  }
  
  if(mode=="/")
  {
      sm= a / b;
  }
  
   cout<<"  "<<endl;
    cout<<"The answer is "<<sm << endl;


    return 0;
}
