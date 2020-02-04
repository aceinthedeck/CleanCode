# Clean Code

## Functions
A function should do one thing.
DRY (Do not repeat yourself)

### Output arguments
Output arguments should be avoided. If the function changes the state of something, have it change the state of its owning object.

### Command query separation
- Functions should either do something or answer something but not both.
- Prefer exceptions to returning error codes.
- Extract try/catch blocks.
- Error handling is one thing.

### Error handling
- Use Exceptions rather than return codes.
- Use unchecked exceptions.
- Provide context with exceptions.
- Don't return null, throw an exception instead.

### Tests
- Tests should follow FIRST - Fast, Independent, Repeatable, Self validating, Timely
- Single concept per test
- Single assert per test
- Three laws of TDD
- First law you may not write production code until you have a failing unit test.
- Second law you may not write more of a unit test than is sufficient to fail.
- You may not write the production code that is sufficient to pass the currently failing test

### Classes
- Classes should be small.
- Class size is measured by responsibilities.
- Single Responsibility Principle, classes should have only one reason to change.
- Cohesion should be high, that is, methods and variables of the class are co-dependent 
