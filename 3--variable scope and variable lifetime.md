Variable scope is the scope where the variable can effect.
Variable lifetime is the time between the variable was defined and destoried.
Local variable's scope is the the function's scope.If the function is finished,the local variable's lifetime will end.
Global variable's scope is the entire project,it can be used in different documents.If the program is finished,the global variable's lifetime will end.

a.c
int global_value = 2022;

b.c
#include <stdio.h>
extern int global_value //extern will import the variable from the other document which is in the same project
int main(){
  printf("global_value is %d",global_value);
  return 0;
}
