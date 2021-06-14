# Hello World

The hello world program in C is shown below.

```c
#include <stdio.h>
int main()
{
  printf("Hello World\n");
  reutrn 0;
}
```

Now let us dissect each element of this "Hello World" code written above.

- `#include <stdio.h>` - The #include is used to include contents of a file in our code. Here, we're including standard input output header file or `stdio.h`. This file contains all the code for input output. C language is in itself very small so we include pre-written code that provides us additional functions within the language.

- `int main()` - In this line we are defining a function called `main()` with return type `int`. The main function is a special function as when the code is compiled it serves as the starting point. The `int` keyword tells the return type of the function.

- `printf("Hello World\n");` - In this line `printf()` is used, which is also function. It is used to print the our message "Hello World". The `printf` is not a part of C language, its a function whose definintion is given in `stdio.h` library. <br>
  There is a `;` in the end of the line, this semicolon is a like a punctuation mark defining the end of the statement.

- `return 0;` - This statement returns value `0` to the `main()` function whose return type is `int`. This value could be any valid integer, the `0` is used to specify that the program exited successfully.

- `{}` - The curly braces where the contents of the code are written. These braces specify a block or in other words starting and end mark, in this case for `main()` function.
