# While Loops
- Executes statments multiple times as long as a condition is true.
- Syntax: `while (<condition>){statment;}`
   - Simpler than for loops
   - Arguably more flexible
   - Use for loops to do for loop things for readability and uniformity
- Alternate Syntax: `do {statement;} while(<condition>);`
   - CONDITION is bottom checked instead of top checked; always executes once

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
