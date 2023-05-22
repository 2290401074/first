There are four types of constant in c++,they are:literal constant,constant variable declared with 'const',identifier constant defined with '#define',enumeration constant.
Here we are introducing these four types.

1.literal constant:
int main(){
  1;
  "abc";
  return 0;
}

2.constant variable declared with 'const':
int main(){
  const int n = 10;
  n = 0;//if we change this variable's value,it will report errors
  printf("n = %d",n);
  int arr1[10] = {0};//define a array include 10 int types,these int types's value are all 0
  int arr2[n] = {0};//the constant variable is a variable essentially,when we  are defining the array's length,it must be a constant.So there will return an error
  return 0;
}

3.identifier constant defined with '#define'
#define MAX 100
int main(){
  #define MIN 1
  int m = MAX;
  int n = MIN;
  printf("m = %d,n = %d",m,n);
  return 0;
}

4.enumerate constant
enum SEX{
  MALE = 3,
  FEMALE
};
int main(){
  enum SEX s = MALE;
  printf("%d",MALE);//3
  printf("%d",FEMALE);//4
  return 0;
}
