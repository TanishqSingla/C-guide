# Comments
Comments are used to convey messages to person reading the code. This makes the code easier to understand. Comments are treated as blank by compilers i.e they won't be treated as a line of code and won't get executed.
### /* */ Comment
This type of comment can create a block of comment. Let's write our hello world program with this comment.
```c
/* 
This is a hello world program written in C language.
*/
#include <stdio.h>
int main(void) /* This is the main function */
{
  puts("Hello World"); /* puts function for printing Hello World */ 
  /* Output
   Hello World
  */
  return 0;
}
```
Now this type of comment would treat every text written between `/*` and `*/` as a comment.

### // Comment
This type of comment was added later in C language. This type of comment is easier to type and can be convinient to place at locations where a whole block is not needed.
```c
/* 
  This is a hello world program made in C langugae. It just shows how to 
*/

//Including libraries
#include <stdio.h>

int main()
{
  puts("Hello World"); // puts function for printing
  return 0;
}
```
Here any text written after `//` is treated as a comment but not the text above, below and before it.