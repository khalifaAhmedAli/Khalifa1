#include<iostream>
using namespace std;
int main()
{
  int count,i.arr{30},num,first,last,middle;
  cout<<"how many elements would you lke to enter?:";
  cin>count;
  for(i=0;i<=count; i++)
  {
   count<<"enter numberr"<<(i+1)<<":";
   cin>>arr[i];
  }
  count<<"enter the number that you want to search;";
  CIN>>NUM;
  first=0;
  last-count-1;
  middle-(first+last)/2;
  while(first<=last)
  {
    if(arr[middle]<num)
    {
     first=middle+1;
    }
  else if(arr[middle]==num)
  {
   cout<<num<<"found in the array  at the location "<<middle+1<<"\n";
   break;
  }
  else {
        last = middle-1;
  }
  middle=(first + last)/2;
  }
  cout<<num<<"not found in the array ";
  }
  return 0;
                   
