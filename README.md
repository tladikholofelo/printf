# _printf

## Description
The function `_printf` writes output to standard output. The function writes
under the control of a `format` string that specifies how subsequent arguments
(accessed via the variable-length argument facilities of `stdarg`) are
converted for output.

## Prototype
```c
int _printf(const char *format, ...);
````

### Return Value

Upon successful return, `_printf` returns the number of characters printed
(excluding the terminating null byte used to end output to strings). If an
output error is encountered, the function returns `-1`.

## Usage

- All files coded on an Ubuntu 20.04 LTS machine with `gcc` using:
```c
gcc -Wall -Werror -Wextra -pedantic -std=gnu89 *.c
````
- All files coded using the `Betty` style and checked using `betty-style.pl` and `betty-doc.pl`


## Authors

> [Lucan Kinnear](https://github.com/lucankinnear) and
> [Kholofelo Tladi](https://github.com/tladikholofelo)

## Acknowledgements

The `_printf` function emulates functionality of the C standard library
function `printf`.
This README borrows from the Linux man page
[printf(3)](https://linux.die.net/man/3/printf).
