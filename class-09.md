# Reading Day: 09.16.20

## Functional Programming
According to Wikipedia, Functional programming is a paradigm, it's a style of building the structure and elements of computer programs that treats computation as the evaluation of mathematical functions and avoids the changing-state and mutable data. 

## Pure Functions
Pure functions return the same result if given the same arguments. It is also referred as deterministic.


## Impure Functions
An example of an impure function would use a global object that was not passed as a parameter to the function. An impure function will read external files and the contents can change. Any function that relies on a random number generator cannot be pure.

This idea of pure functions is new and is a bit abstract right now. Pure functions are stable, consistent and return predictable results.

## Pure Benefits
Pure Functions are easier to test with different contexts:

- **Given a parameter **A** -> Expect the fuction to return value **B**.

- **Given a parameter **C** -> Expect the functioning to return value **D**.

Pure Functions are immutable. They are unchanging over time or unable to be changed.
When Data is immutable, it's state cannot change after it's created. You have to create a new object with the new value.

## Recursive data types
Recursion is a technique for representing data whose exact size is unknown to the programmer: the programmer can specify this data with a self-referential definition. There are two types of self-referential definitions: inductive and co-inductive definitions.

With recursion, we keep our variables immutable.

## Referential Transparency
If a function consistently yields the same result for the same input, it is referentially transparent.

**Pure Functions + Immutable Data = referential Transparency**

## Map Method
This method transforms a collection by applying a function to all of its elements and building a new collection from the returned values.

## Refactoring JavaScript
As I am getting more comfortable with understanding JavaScript I'm identifying the syntax a spacing and realizing how important it is to clearly write code that is easy to read for other developers. This last article caused me to think of what it means to write 'clean code'.

[<== Back to Table of Contents](index.md)