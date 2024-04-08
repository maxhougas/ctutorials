# Switch statements
- Offers conditional execution
- Syntax: `switch(<var>) {case <val>: <statement>; break; ... default: <statement>; break;}`
   - VAR must be an integer
   - skipping breaks is premitted, but subsequent statments will be executed
- Can execute faster than if trees

```c
#include <stdio.h>

int main(int argc, char** argv)
{
 switch(argc)
 {
  case 0:
   printf("argc is 0!\n");
   break;
  case 1:
   printf("argc is 1!\n");
   break;
  default:
   printf("argc is something else!\n");
 }

 return 0;
```
