Array is a container to store a series of data.

int main(){
  int arr1[10] = {1,2,3,4,5,6,7,8,9,10};
  char arr2[5] = {'a','b','c'};//if a array's capacity is larger than its stored content acutually,the last volumn will be replaced by "\0"
  int i = 0;
  while (i<10){
    printf("%d",arr1[i]);//when defining an array,this i must be a constant.But this array has defined in the line 4,so that i can be a variable.
    i++;
  }
  return 0;
}
