There are seven different data types in c++,they are char/short/int/long/long long/float/double

#include <stdio.h> //import headers document to announce the function like printf
int main() //main is stand for this function is the first running function,int is a data type,it means this function will return a int type 
{
  printf("%d",sizeof(char)); //sizeof will return the occupation of the Bytes occupied,%d is a formatting method,it will force the result converse into the int type
  return 0;//0 is a int type
}

Different data types has different Bytes occupied
char 1
short 2
int 4
long 4
long long 8
float 4
double 8
