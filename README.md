# Project - Printf

> This project aims at replicating the C standard library `printf()` function. This is done incrementally by handling specific issues; from just writing a function that produces output according to a format, handling conversion specifiers and custom conversion specifiers, using a local buffer of 1024 chars in order to call `write` as little as possible, handling flag characters for non-custom conversion specifiers such as space, +, #, handling length modifiers for non-custom conversion specifiers such as l ,h, handling the field width for non-custom conversion specifiers, handling the precision for non-custom conversion specifiers, handling the `0` flag character for non-custom conversion specifiers, handling the `-` flag for non-custom conversion specifiers, handling the `r` custom conversion specifier that prints the reversed string, handling the `R` custom conversion specifier for printing the rot13'ed string, and finally ensuring that all these work well together.

## Built With

- Major Languages: C
- Tools: VSCode, Vim
