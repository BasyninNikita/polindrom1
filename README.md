#include <iostream>
#include <string>
using namespace std;
int main()
{
string str;
cout<<"enter the word:";
cin>>str;
int dl= str.length();
int j=0;
for(int i=0;i!=dl/2;i++)
{
   if(str[i]!=str[dl-i-1])
   {
      cout<<"0";j=1;break;
}
}
if(j==0)
{
   cout<<"1";
}
    return 0;
}
