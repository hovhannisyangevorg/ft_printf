# ft_printf

Welcome to ft_printf! This is a project from the 42 programming school that aims to recreate the functionality of the standard printf function in C. The goal of this project is to build a custom printf function that can handle various format specifiers and output formatted text.

## Getting Started

To use this printf implementation, you can simply clone the repository and compile the `libftprintf.a` library by running the `make` command:
```bash
  git clone https://github.com/hovhannisyangevorg/ft_printf.git
```
```bash
  cd ft_printf
```
```bash
  make
```


This will compile the source files and create the `libftprintf.a` library file.

You can then link this library to your own projects by including the `ft_printf.h` header file and adding the
library path and name \n (`-L/path/to/ft_printf -lftprintf`) to your compilation command.

## Project Structure

The project is organized as follows:

- `src/`: Directory containing the source code files for ft_printf and supporting functions.
- `obj/`: Directory where the object files will be created during compilation.
- `include/`: Directory containing the header files for ft_printf and supporting functions.
- `Makefile`: Contains the compilation rules for building the library.

## Supported Format Specifiers

The ft_printf function supports the following format specifiers:

- `%c`: Character
- `%s`: String
- `%d` or `%i`: Signed decimal integer
- `%u`: Unsigned decimal integer
- `%x` or `%X`: Unsigned hexadecimal integer (lowercase/uppercase)
- `%p`: Pointer
- `%%`: Percentage sign

Please refer to the provided `ft_printf.h` header file.

## Documentation

The `ft_printf.h` header file contains all the necessary function prototypes and definitions to use ft_printf. Please consult this file to understand how to use the function and the format specifiers.
