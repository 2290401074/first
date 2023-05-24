Function is a useful tool.When you need to solve a problem many times,function can be helpful

int add(int x,int y){//this function will return a int type
  int z = 0;
  z = x+y;
  return z;
}
int main(){
  int a = 0;
  int b = 0;
  scanf("%d%d",&a,&b);
  int sum = add(a,b);
  printf("%d",sum);
  return 0;
}
