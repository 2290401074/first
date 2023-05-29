The operators are very important in c++,here are these types.

Arithmetic operators:
+
-
*
/  //this division sign will only return the int type,like:9/2=4.If you want a float type,try:9/2.0=4.50000
%  //this sign called modulo symbol,it will return the remainder of division

Shift operators:
<<  //left shift operator
>>  //right shift operator
int main(){
  int a = 1;
  int b = a<<2;//a will left shift 2 times
  printf("%d\n",b)//a is 00000000000000000000000000000001,it will be 00000000000000000000000000000100
  return 0;
}

Bitwise operators:
&  //bitwise AND operator
|  //bitwise OR operator
^  //bitwise XOR operator
~  //bitwise NOT operator
int main(){
  int a = 0;//There are three number type，they are signed magnitude,one's complement,two's complement.The computer use the two’s complement to express the number.
            //a's signed magnitude is 00000000000000000000000000000000
            //a's one's complement is 01111111111111111111111111111111
            //~a is 11111111111111111111111111111111
  printf("%d\n",~a)//-1's signed magnitude is 10000000000000000000000000000001
                   //-1's one's complement is 11111111111111111111111111111110
                   //-1's two's complement is 11111111111111111111111111111111 just equal to the ~a,so ~a = -1
  return 0;
}

Assignment operators:
=
+=
-=
*=
/=
&=
|=
^=
<<=
>>=

Unary operators：
！
-
+
&
sizeof  
--  //b = --a will let a+=1 then let b = a,b = a-- will let b = a then let a+=1
++ 
(type) //(int)3.14 = 3

Logical operators:
&&  //and
||  //or 

Conditional operator:
exp1?exp2:exp3
int main(){
  int a = 0
  int b = 0
  scanf("%d%d",&a,&b)
  max = a>b?a:b // if a>b,max = a,else max = b
  return 0;
}

Comma operator:
exp1,exp2,exp3,....,expn
int main(){
  int a = 1
  int b = 2
  int c = 3
  int d = (a+=1,b+=a,c+=b) //d = 7 ,this d will accept the last exp's result
  return 0;
}
