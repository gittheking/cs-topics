# Data structures
## Learning objectives
- SWBAT identify different types of simple data structures
- SWBAT identify different scenarios where certain data structures are more important

## Primitive values
in JS: All data types except objects.
- Boolean: True/False
- Null: has exactly one value, `null`
- Undefined: a variable that has not been assigned a value
- Number: in JS there is only one Number type, which is double precision 64 bit binary format, ranges from -(2^53 - 1) and (2^53 - 1). There is no specific type for integers.
  - Other values in the Numbers type:
  `Infinity`,`-Infinity`, `NaN`
- String: represents textual data. In JS strings are immutable, meaning you cannot modify strings in JavaScript.
- Symbol type: this is new to ES6, is a unique and immutable primitive value and may be used as the key of an Object property.

## Data Structures
Organization of data.

##Stacks
a stack is a way of organizing data in a way that it has LIFO operation, that means thats the last element being entered into the stack will be the first one out.

- A stack is either empty or consists of a top and the rest of the stack

### operations
- Push
- Pop
- Top

### Applications
- The simplest applications of a stack is to reverse a word. You push the letters of a word into a stack and then just pop them out.

- Stacks are used for the `undo` mechanism in any type of editor.

- Stacks can be used for backtracking. This can be used for a binary tree or even a maze. Think once you reach a dead end you must backtrack until you have more choices of direction.

- Language processing:
  - can be used to match parenthesis, double/single quotations, etc. Also can be used to parse through HTML

## Queues
- FIFO
-  
