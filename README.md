# C++ Date Period Overlap

A C++ console application that determines whether two date periods overlap.

The project builds on date comparison logic and introduces structured periods using nested structures.

## Features

- Compare two dates
- Determine whether dates are before, equal, or after each other
- Represent a date using a structure
- Represent a date period using a structure
- Detect whether two periods overlap
- Read complete periods from user input

## Concepts Practiced

- C++ Structures
- Nested Structures
- Enumerations
- Functions
- Const References
- Conditional Operators
- Boolean Logic
- Date Comparison
- Problem Solving
- Code Organization

## Data Structures

The project uses `stDate` to represent a date:

```cpp
struct stDate
{
    short Year;
    short Month;
    short Day;
};
