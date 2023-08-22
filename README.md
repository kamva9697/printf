# ALX _printf Project

A formatted output conversion C program completed as part of the low-level
programming and algorithm track at ALX. The program is a pseudo-
recreation of the C standard library function, `printf`.

## Usage

To use the `_printf` function, compile all `.c` files in the repository and include the header `main.h` with
any main function.

Example `main.c`:
```
#include "main.h"

int main(void)
{
    _printf("Hello, World!");

    return (0);
}
```

Compilation:
```
$ gcc *.c -o tester
```

Output:
```
$ ./tester
Hello, World!
$
```
