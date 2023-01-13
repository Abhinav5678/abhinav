# abhinav
program for finding sum of two number using usinf function. in c pgram
#include <stdio.h>

int sum (int num1, int num2);

int
main ()
{
  int num1, num2, result;
  printf ("enter the two number-:");
  scanf ("%d %d", &num1,&num2);

  result = sum (num1, num2);

  printf ("addition of two number is -:");
  return 0;
}


int
sum (int num1, int num2)
{
  int num3;
  num3 = num1 + num2;
  return num3;
}
