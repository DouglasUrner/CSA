# AP Computer Science A (CSA) Course Notes

## Refactoring

* Look for:
  - Complexity to break up.
    - Compound Booleans, instead make the test in a well named method that explains the purpose of the Boolean.
    - Local variables, in Ruby make the local a method (since everything is an object calling the method cum variable with out arguments has the same effect as refering to a variable).
    - Inline comments, they are clues to where you can break the code into methods - use the comment to help you name the method.
  - Duplication to combine.
  - Abstractions to create.
