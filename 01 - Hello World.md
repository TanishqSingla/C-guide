# Hello World
Let's start with a basic hello world program, which just prints out the output to screen.
```c
#include <stdio.h>
int main() 
{
  printf("Hello World");
  reutrn 0;
}
```
Now let's dissect each element of this code.
`#include <stdio.h>` - The #include is used to include contents of a file in our code. Here, we're including standard input output header file or stdio.h. This file contains all the code for standard input output.\
`int main()` - Here we are initializing a function called `main()`. Now main function is different then any other function.\
`printf("Hello World");` - In this line `printf()` is used, which is a function that prints the our message "Hello World".\
If you noticed well, there is a `;` in the end of the line, this semicolon terminates our statement.

**Note** - Semicolons are very important, since th
