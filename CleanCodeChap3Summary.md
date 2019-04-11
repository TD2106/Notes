# Summary on the 3rd video of clean code series

Chapter 3 is about function

  - The main point I learn in chapter 3 is that a function should only have one single purpose, and the function should do it well
  - A function should have a maximum of 20 lines of code
  - Don't worry about creating so many functions, the compiler and the machine are fast enough to handle the call satack
  - A function should have only one if else or try catch block, as in as little indenting as possible
  - According to the above rule, a bracket (if/else, while/for loop, try/catch) is a chance for refactorization
  - As always a function should be well named
  - The function will served as checkpoints for navigating around the code base
  - Functions should be written in top down method, the caller should be written ahead of the callee, so that the we can read the code base
  in a fashion similar to reading books or newspaper
  - One level of abstraction per function, but level of abstraction can be fuzzy, just follow the rule extract till you drop, as in keep extracting
  the function into smaller functions till you can't anymore
  - As few arguments as possible, 3 to 4 top
  - Have no side effect, corresponding to single responsibily principle
