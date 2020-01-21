# Clean Code

## Functions
A function should do one thing.
DRY (Do not repeat yourself)

### Output arguments
Output arguments should be avoided. If the function changes the state of something, have it change the state of its owning object.

### Command query separation
Functions should either do something or answer something but not both.
Prefer exceptions to returning error codes.
Extract try/catch blocks.
Error handling is one thing.
