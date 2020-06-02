# Hello World
Let's start with a basic hello world program, which just prints out the output to screen.
```c
#include <stdio.h>
int main() 
{
  printf("Hello World\n");
  reutrn 0;
}
```
Now let's dissect each element of this code.
`#include <stdio.h>` - The #include is used to include contents of a file in our code. Here, we're including standard input output header file or stdio.h. This file contains all the code for standard input output.\
- `int main()` - Here we are initializing a function called `main()`. Now main function is different then any other function, we'll see in the functions section.
- `printf("Hello World\n");` - In this line `printf()` is used, which is a function that prints the our message "Hello World".\
If you noticed well, there is a `;` in the end of the line, this semicolon terminates our statement of calling the function `printf()`.
- `return 0;` - This statement return value 0 to the `main()` function whose return type is an integer. This value could be any valid integer, we use 0 just to specify that the program exitted successfully.
- `{}` - The curly braces. The contents of the code are written. These braces specify a block and this block is the binds our content to main() function.
