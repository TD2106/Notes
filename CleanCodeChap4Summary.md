# Clean code chap 4 summary

## The focus of chap 4 is function arguments
  - Function should have as few arguments as possible, 3 to 4, if more can probably be passed as an object or create another function (similar
  to the point I mentioned in chap 3 summary, maybe my memory lapsed because I read the book first)
  - Command and Query separation. When a method return some value, it shouldn't do anything to change the state of the system, when a method
  doesn't return anything (void), it should change the state of the system
  - Step down rule, the function at the top should be high level, the function at the bottom should be low level, kinda similar to the approach
  of writing the method in a top down manner.
  - Try/catch, if/else should be the first and last keyword for the function, no other code before and after them
  - Inside each try catch, if else block should be a function
  - We should write predicate function for use as condition inside if else clause
  - Avoid the use of switch, instead use interface to decouple the dependency directly
  - Then comes some of the part which I don't understand like dependency injection, maybe I haven't worked on a system of such scale to understand
  
