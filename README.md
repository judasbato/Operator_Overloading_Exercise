# Operator Overloading Exercise

This project is a C++ exercise demonstrating the concept of operator overloading using a custom string class called `Mystring`. The `Mystring` class implements various operators to perform operations such as concatenation, comparison, case conversion, repetition, and more.

## Files

- **Mystring.h**: Header file containing the declaration of the `Mystring` class along with prototypes for overloaded operators and member functions.
- **Mystring.cpp**: Implementation file containing the definitions of member functions of the `Mystring` class and overloaded operators.
- **main.cpp**: Main program demonstrating the usage of the `Mystring` class and its overloaded operators.

## Features

### Constructors and Destructors
- Implements default constructor, overloaded constructor, copy constructor, move constructor, and destructor for managing dynamic memory allocation.

### Operator Overloading
- Overloads various operators including `=`, `==`, `!=`, `<`, `>`, `+`, `+=`, `-`, `*`, `*=`, `++` (prefix and postfix), `<<`, and `>>` to perform string manipulation and comparison operations.

### Member Functions
- Includes member functions for string display, getting string length, and getting the string itself.

## Usage

The `main.cpp` file provides examples of how to use the `Mystring` class and its overloaded operators. It demonstrates various operations such as string comparison, concatenation, case conversion, repetition, and more.

## Getting Started

To run the provided example program:
1. Clone this repository to your local machine.
2. Compile the source files using a C++ compiler.
3. Execute the compiled program.

```bash
g++ main.cpp Mystring.cpp -o mystring_app
./mystring_app 
```
Follow the prompts in the program to interact with the Mystring class and observe the results of different operations.
