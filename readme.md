# JavaScript Tutorial

### inner html

- responsible for what is being displayed on a webpage

### Array methods:

- shift(): remove first element of the array
- push(): add elemet at end of array
- pop() : remove last element from array
- unshift(): add first element in array
- concat(): to merge two different array
- sort() : sort entire array into ascending order
- reverse(): reverse elemet of array
- join(): returns array as a string and add string

### Map,reduce and filter

- map(): create a new array and performs a function on each array element and doesn't change the original array
- filter(): takes each elemet in an array and applies conditional statement
- reduce(): reduces an arrya of values down to just one value using a function

### loops

- break: to terminate the loop
- continue: to skip a particular loo[
  - to use continue in while loop you should do the increment inside the condition check before continue

### object

Objest ia a collection of properties

- Js is template based and we can create objects without need of having a class
- 3 diffrent way of creating js object
  - use object literal
  - use keyword new
  - use an object constructor

###### object properties:

- value associated with js object are its properties
- properties can be added, updated, and deleted, excluding read-only properties

##### object methods:

- action that can be performed on the object

- js object accessors
  - getter: to get the value of the properties of an object
  - setter : to set th value

### function

- js function can be stired in variable
- function constructore: new Function()

##### self invoking function

- invoked automatically without being called
- enclosed inside paranthesis
- to call add paranthesis at the end of function

##### function as values

- we define funcation then assign it to a variable unlike in expression

##### funcation as objects

- includes string which holds actual code i.e function body of function

##### arrow function

- cannot be used as constructors

##### generator functions

- can return multiple values
- make use of '\*': function\*
- main method of generatir function is next() method
- until yield value is completed and return to outer code
- result is always object with two property: value and done

##### JSON.stringify()

- it cnverts js value or object to hson string

##### pre-defined function

- eval: evaluates string and returns a value
- parseInt: Parses a string argulemt and retuns an integer
- escape: returns hexadecimal encoding of an argument
- unescaoe: return the ascii sring for specified value
