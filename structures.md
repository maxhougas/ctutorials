# Structures
- An irregular datatype
- Often used with typedef
- Syntax: `typedef struct{<stuff>;} label;`
   - Often used with malloc() from stdlib.h

```c
#include <stdio.h>
#include <stdlib.h>

typedef struct
{
 int data;
 void* next;
} node;

int main(int argc, char** argv)
{
 node n0;
 node* n0_p = &n0;
 n0_p -> data = 1337;
 n0_p -> next = (void*)1338;

 printf("Let's look inside our node!\n");
 printf("Data: %d\nNext: %ld\n",n0.data,(long int)n0.next);

 return 0;
}
```
