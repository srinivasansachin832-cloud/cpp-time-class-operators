# C++ Time Class Operator Overloading

A C++ project that implements a `Time` class with overloaded operators for formatted input/output, comparisons, arithmetic operations, and increment behavior.

## Overview
This project models time as a custom C++ data type and extends the class with overloaded operators to support natural syntax for printing, reading, comparing, adding, subtracting, and incrementing time values.

## Features
- Overloaded stream operators `<<` and `>>`
- Comparison operators `==`, `!=`, `<`, `>`
- Arithmetic operators `+`, `-`, `+=`, `-=`
- Pre- and post-increment operators `++`
- 12-hour and 24-hour time conversion logic
- Multi-file C++ class implementation

## Files
- `Time.h` - class declaration and operator prototypes
- `Time.cpp` - class methods and operator definitions
- `main.cpp` - test/demo driver for the Time class
- `RTC.cpp` - supporting test case driver (if included)

## Concepts Used
- Object-oriented programming
- Operator overloading
- Constructors
- Encapsulation
- Formatted input/output
- Time arithmetic
- Multi-file project organization

## Example Operations
- Read times such as `7:30 PM`
- Compare two `Time` objects
- Add and subtract times
- Increment a time value by one minute

## How to Compile
Using g++:

```bash
g++ main.cpp Time.cpp RTC.cpp -o timeapp
./timeapp
