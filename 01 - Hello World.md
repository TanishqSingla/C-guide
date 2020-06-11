# Hello World
Let's start with a basic hello world program, that prints out the "Hello World" on the screen.
```c
#include <stdio.h>
int main() 
{
  printf("Hello World\n");
  reutrn 0;
}
```
Now let us dissect each element of this "Hello World" code written above.
- `#include <stdio.h>` - The #include is used to include contents of a file in our code. Here, we're including standard input output header file or stdio.h. This file contains all the code for standard input output. C language is in itself very small so we include pre-written code to work which provides us additional functionalities within the language.
- `int main()` - Here we are initializing a function called `main()`. The main function is a special function as when the code is compiled it serves as the starting point.
- `printf("Hello World\n");` - In this line `printf()` is used, which is a function that prints the our message "Hello World". The `printf` is not a part of C language, its a function whose definintion is given in `stdio.h` library.\
If you noticed well, there is a `;` in the end of the line, this semicolon terminates our statement of calling the function `printf()`.
- `return 0;` - This statement return value 0 to the `main()` function whose return type is an integer. This value could be any valid integer, we use 0 just to specify that the program exitted successfully.
- `{}` - The curly braces where the contents of the code are written. These braces specify a block and this block is the binds our content to main() function.
\
\
Since `printf()` is just a function and not a part of C language the above code can be alternatively written as
```c
#include <stdio.h>
int main()
{
  puts("Hello World");
  return 0;
}
```
