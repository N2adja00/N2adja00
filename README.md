#include <stdio.h>
main()
{
 int A,B;
 int MAX;
 printf("Geben Sie zwei ganze Zahlen ein :");
 scanf("%i %i", &A, &B);
 if (A>B)
     MAX=A;
 else
     MAX=B;
 printf("Der maximalwert ist %i\n", MAX);
  return 0;
}
