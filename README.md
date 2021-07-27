# _printf :page_facing_up:

A formatted output conversion C program completed as part of the low-level
programming and algorithm track at Holberton School. The program is a pseudo-
recreation of the C standard library function, `printf`.

created by Faji Sultan and Ibrahim sultan

## Dependencies :couple:

The `_printf` function was coded on an Ubuntu 14.04 LTS machine with `gcc` 

## Usage :running:

To use the `_printf` function, assuming the above dependencies have been installed,
compile all `.c` files in the repository and include the header `holberton.h` with
any main function.

Example `main.c`:
```
#include "holberton.h"

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



### Return Value

Upon successful return, `_printf` returns the number of characters printed
(excluding the terminating null byte used to end output to strings). If an
output error is encountered, the function returns `-1`.

## Authors :black_nib:

* Faji Sultan <[faji](https://github.com/faji-75)>
* Ibrahim Sultan <[ibrahim](https://github.com/ibrahim1793)>

