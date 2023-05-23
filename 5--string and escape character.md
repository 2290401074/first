String literal is a special data type,it can be announced by double quotation marks.In the other way,character literal is announced by single quotation mark。

#include <stdio.h>
#include <string.h>

int main(){
  char arr1[] = "abc";//string literal has a hidden null character '\0',it is used to mark the end of the string
  char arr2[] = {'a','b','c'};
  printf("%s\n",arr1);//abc
  printf("%s\n",arr2);//abc etc.
  printf("%d\n",strlen(arr1));//strlen is a function to carculate the string's length//3
  printf("%d\n",strlen(arr2));//a random number
  return 0;
}

Escape character is a series of characters whose meaning was changed.
For example,"\n" can break the line,"\ddd" can force the decimal number converse into the octal number,also "\xdd" can force the decimal number converse into the hexadecimal number.
