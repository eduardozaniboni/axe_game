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

### 19. Moving the Circle

#### Summary

- The "if" statement
- Detect key presses
  - Used "IsKeyDown()"
    i. KEY_D
    ii. KEY_A

### 20. Logical AND

#### Summary

- Learned about the logical AND
- Used "&&" to add boundaries

### 21. Drawing the Axe

#### Summary

- Used "DrawRectangle()" to draw the axe
- Learned about "+=" and "-="
  - Used these in our code

### 22. Logical OR

### Summary

- Logical OR
- Used "||" to detect when the axe hits the edge
  - Reverse the axe's direction

### 23. Collision Detection

- Collision detection
- Dimensions of the circle
  - Circle radius
- Dimensions of the axe
  - Axe length
- Created variables for the collision boxes

### 24. The else Statement

#### Summary

- The "else" statement
  - Always goes with "if"
- "DrawText()"
- Created bool "collision_with_axe"
  - When "true", print "Game Over!"
  - When "false", draw the circle and the axe

### 24. Finishing the Game

#### Summary

- Used "&&" to give "collision_with_axe" the correct value.
- Created a Game over state for our game!
- Congratulations!!!