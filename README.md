# leap_year


#include <iostream.h>

#include <conio.h>

#include <iomanip.h>

using namespace std;

 

int main()

{

   int year;

   cout<<"Enter a year"<<endl;

   cin>>year;

   if(year%4==0&&year%100!=0||year%400==0)

   {

       cout<<"It is a leap year"<<endl;

   }

   else

   {

       cout<<"It is not a leap year"<<endl;

   }

   getch();

   return 0;

}

 


 


