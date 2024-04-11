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
#define LOOPSTOP 5

int main(int argc, char** argv)
{

 int timeslooped=0;

 while(timeslooped < LOOPSTOP)
 {
  if(timeslooped == 3)
  {
   printf("timeslooped is 3, continuing!\n");
   timeslooped++;
   continue;
  }
  printf("Looped %d times!\n",timeslooped);
  timeslooped++;
 }

 /*timeslooped=0;

 do
 {
  printf("Looped %d times!\n",timeslooped);
  timeslooped++;
 } while(timeslooped < LOOPSTOP);*/

 return 0;
}
```
