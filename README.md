# Axe Game

## Section: 2

### 10. Creating A Popup Window

#### Summary

- Two ways to include libraries
  - Standard Libraries (<...>)
  - External Libraries ("...")
- InitWindow
  - Takes multiple input parameters
  - Passed in as comma-separeted (,) list

```cpp
#include "raylib.h"
int main()
{
    InitWindow(1280, 720, "First Window");
}
```

### 11. Data Types and Variables

#### Summary

- Data types
- Integers
  - Whole numbers
  - Cannot have a fractional part
- Declaring a new variable
  - Specify the type and name
  - Assign a value using = (equals)

### 12. Data Types and Variables 2

#### Summary

- Data types
  - Floating Point
    i. float
    ii. double
  - Boolean
    i. bool
- Unused variables

### 13. Debugging

#### Summary

- Debugging
  - Placing breakpoints
  - Step into
- Observe values
  - Garbage data
  - Ways to initialize

### 14. Comparasion Operators

#### Summary

- Comparison operators
  - Compare two values
  - Return a bool
- Expression
  - Operators
  - Operands
  - Return a value
- Created some variables

### 15. Loops

#### Summary

- Loops
  - Repeat code
- "while" loop
  Loop condition
- Infinite loops

### 16. Clear the Background

#### Summary

- BeginDrawing() and EndDrawing()
  - Setup and teardown
- ClearBackground();
  - Clears the canvas to a color
  - Must call this to avoid flickering

### 17. Function Return Values

#### Summary

- Function Return Values
- "WindowShouldClose()"
  - Close our window

### 18. Drawing a Circle

#### Summary

- Used "DrawCircle()" to draw a circle!
- Coordinates
  - Placed the circle at the center
