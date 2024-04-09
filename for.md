# Switch statements
- Executes statments multiple times (usually a set number)
- Syntax: `for(<init>;<conditional>;<modifier>){<statment>;}`
   - INIT is executed before the first before of the loop
   - CONDITONAL is executed at the top of each iteration of the loop. Must evalute to an int.
   - MODIIFIER is executed at the bottom of each iteration of the loop.
- Offers more freedom than you might expect

```c
#include <stdio.h>
#define LOOPSTOP 3

int main(int argc, char** argv)
{

 /*int loopstop = 5;*/
 int i,j;

 for(i=0;i<LOOPSTOP;i++)
 {
  for(j=0;j<i;j++)
   printf("#");
  printf("\n");
 }

 return 0;
}
```
