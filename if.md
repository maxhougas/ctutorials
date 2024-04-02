# If statements
- Offers conditional execution
- Syntax: `if(<conditional>)`
   - Conditional must evaluate to an integer
   - 0 is false; 1 is true
   - == is a binary operator that returns an integer
   - else block executes on false
- Can chain together to make if-else trees

```c
#include <stdio.h>

int main(int argc, char** argv)
{
 if(argc == 0)
  printf("argc is 0!\n");
 else if(argc == 1)
  printf("argc is 1!\n");
 else
  printf("argc is something else!\n");

 return 0;
}
```
