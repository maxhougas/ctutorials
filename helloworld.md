# Hello, World
- The ancient concord
- Must include stdio.h
- Main() should return an int and take an int and a char**
   - argc is the number of arguments
   - argv is the argument vector
- Remember to return 0
- Printf() needs a \n
   - crlf for Windows
   - nl for Linux
- compile with `gcc -ansi -o <name>.o <name>.c`

```c
#include <stdio.h>

int main(int argc, char** argv)
{
 printf("Hello, kitty!");
 return 0;
}
```
