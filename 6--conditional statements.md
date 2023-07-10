When the progress meet some conditions,if this condition is true it will execute corresponding code,this condition called conditional judgement.

int main(){
  int input = 0;
  printf("Yes or no 1/0");
  scanf("%d",&input);
  if (input==1)
  {
    printf("Yes");
  }
  else
  {
    printf("No");
  }
  return 0;
}

int main(){
  int line = 1;
  while (line<10000)
  {
    printf("line = %d",line++);
  }
  printf("line is 10000");
  return 0;
}
