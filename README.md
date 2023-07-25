# printf Project

## Description
This project is part of the ALX curriculum, and it involves creating a custom implementation of the printf function in the C programming language. The printf function is a fundamental function in the C standard library that is used to print formatted output to the console.

The goal of this project is to gain a deeper understanding of the inner workings of the printf function and to develop skills in using variadic functions and managing a large codebase.

## Getting Started
To use this printf function, simply include the my_printf.h header file in your C program, and then call the my_printf function with the desired format string and arguments.

### Here's an example usage:
```c
#include "main.h"

int main() {
    int num = 42;
    double pi = 3.14159;
    char *str = "Hello, world!";
    _printf("The number is %d, the string is %s, and pi is %f\n", num, str, pi);
    return 0;
}
```
This will output: The number is 42, the string is Hello, world!, and pi is 3.141590.

### Supported Format Specifiers
The printf function supports a wide range of format specifiers that allow for the formatting of output in a variety of ways. Here are the format specifiers that are supported in this implementation of printf:

`%d: for integers`<br>
`%s: for strings`<br>
`%f: for floats/doubles`<br>
`%b: for binary`<br>
`%u: for unsigned integers`<br>
`%o: for octal numbers`<br>
`%x: for hexadecimal numbers (lowercase)`<br>
`%X: for hexadecimal numbers (uppercase)`<br>
`%S: for non-printable characters`<br>
`%p: for pointer addresses`<br>
`%r: for reversed strings`<br>
`%R: for rot13'ed strings`<br>

# Tasks
The printf project is broken down into several tasks, each of which focuses on a specific aspect of the printf function. Here's a brief overview of the tasks that are involved in this project:

## Task 0
Write a function that produces output according to format. This task involves implementing the basic functionality of printf, and it handles conversion specifiers c and s.

## Task 1
Handle conversion specifiers d and i. This task involves adding support for integer conversion specifiers to the printf function.

## Task 2
Create a man page for the function. This task involves writing a manual page that documents the usage and functionality of the printf function.

## Task 3
Handle conversion specifier b. This task involves adding support for binary conversion specifiers to the printf function.

## Task 4
Handle conversion specifiers u, o, x, and X. This task involves adding support for unsigned integer, octal, and hexadecimal conversion specifiers to the printf function.

## Task 5
Use a local buffer of 1024 chars in order to call write as little as possible. This task involves optimizing the printf function to minimize the number of calls to the write function, which can improve performance.

## Task 6
Handle custom conversion specifier %S. This task involves adding support for a custom conversion specifier that prints non-printable characters in a specific format.

## Task 7
Handle conversion specifier p. This task involves adding support for pointer address conversion specifiers to the printf function.

## Task 8
Handle flag characters \+, space, and \#. This task involves adding support for flag characters that modify the formatting of the output.

## Task 9
Handle length modifiers l and h. This task involves adding support for length modifiers that change the size of the data types that are printed by the printf function.

## Task 10
Handle field width. This task involves adding support for specifying a minimum field width for the output.

## Task 11
Handle precision. This task involves adding support for specifying the precision of floating point numbers that are printed by the printf function.

## Task 12
Handle flag character 0. This task involves adding support for a flag character that pads the output with zeros.

## Task 13
Handle flag character -. This task involves adding support for a flag character that left-aligns the output.

## Task 14
Handle custom conversion specifier %r. This task involves adding support for a custom conversion specifier that prints reversed strings.

## Task 15
Handle custom conversion specifier %R. This task involves adding support for a custom conversion specifier that applies the rot13 encryption algorithm to strings.

## Task 16
All the above options work well together. This task involves testing the printf function to ensure that all of the implemented features work correctly and that there are no conflicts between them.

---

### Authors
* **BENSOUDA EL MEHDI** - [bensoudamehdi6@gmail.com](https://github.com/ElMehdi02)
* **OUSSAMA EL MEFTAHI** - [elmeftahioussama@gmail.com](https://github.com/osmmf)
