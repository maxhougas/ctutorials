# Pointers
- An integer that refers to a memory address
- Syntax: `<type>* <label> = &<defined_variable>;`
   - Often used with malloc() from stdlib.h
   - Can be used to pass multiple values in array form

```c
#include <stdio.h>
#include <stdlib.h>

int main(int argc, char** argv)
{
 int leet;
 int* leet_p = &leet;
 *leet_p = 1337;

 printf("The 1337 number is %d\n",*leet_p);

 return 0;
}
```
