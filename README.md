# write-a-program-in-c-that-use-for-loop-to-print-out-the-multiplication-table-of-a-given-number-en
-
#include <stdio.h>
int main(){
   int i, num;
   /* Input a number to print table */
   printf("Enter number to print table: ");
   scanf("%d", &num);
   for(i=1; i<=10; i++){
      printf("%d * %d = %d
", num, i, (num*i));
   }
   return 0;
}
