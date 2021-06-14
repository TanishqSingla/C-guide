# Comments

Comments are treated as blank by compilers i.e they are completely ignored by the compiler and therefore doesn't execute.

This makes comments useful as they can be used to add meaning to the line/block of code and can also be used to convey a message to other programmer or yourself when reading the code later.

### Block Comment

Block comment can be created by enclosing the text between `/*` and `*/`.

```c
/*
This is a hello world program written in C language.
*/
#include <stdio.h>
int main(void) /* This is the main function */
{
  printf("Hello World"); /* puts function for printing Hello World */
  /* Output
   Hello World
  */
  return 0;
}
```

### Line Comment

This type of comment was added later in C language. This type of comment is easier to type and can be convinient to place at locations where a whole block is not needed.

```c
/*
  This is a hello world program made in C languge.
  This code shows the usage of line comment.
*/

// Includeing standard input output library.
#include <stdio.h>

int main()
{
  printf("Hello World"); // puts function for printing
  return 0;
}
```

Here any text written after `//` is treated as a comment but not the text above, below and before it.
