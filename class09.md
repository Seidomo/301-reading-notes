#  FUNCTIONAL PROGRAMMING

Functional programming is a programming paradigm style of building the structure
and elements of computer programs that treats computation as the evaluation of mathematical function and avoids changing-state and mutable data. (Taken from Wkipedia).



**PURE FUNCTION**

- Is a function that returns the same result if given the same arguments.

- Are function that are stable, consistent and predictable.

**IMPURE FUNCTION**

- Is a function that uses a global object that was not passed as a parameter.

- A function that reads external file.

- A function that relies on a random number generator.

**IMMUTABILITY**

Its a data that is unable to be changed instead you create a new one.

```
PURE FUNCTION + IMMUTABLE DATA = REFERENTIAL TRANSPARENCY

```

###  **HIGHER ORDER FUNCTION**

- Are functions that take one more functions as arguments or 
  return functions as a result.

  **FILTER**

Is a method given a collection that filters using an attribute and expectes
a true or a false value to determine if the element should or should not be 
included in the result.

  **MAP**

Is a method that transforms a collection by applying a function to all its elements
and returns a new collection of returned values.













* [Reference](https://medium.com/the-renaissance-developer/concepts-of-functional-programming-in-javascript-6bc84220d2aa)