# SQL Functions

## Introduction
This paper will cover the uses of user-defined functions in SQL and the differences between scalar, inline, and multi-statement functions.

## User-Defined Functions
There are many built-in functions in SQL that users can use when writing queries. SQL also allows users to create and store their own functions in a database. Functions return database objects and can take parameters. UDFs can be used in queries to transform data or check constraints. Being able to take parameters means functions are not limited to being called with a SELECT statement like views. Functions can be used within SELECT statements, views, and even other functions to transform data.

## Scalar, Inline, and Multi-Statement Functions
A function that returns a single value instead of a table is a scalar function. The most simplistic of functions require only a single statement to return the desired object. These are known as inline functions. More complex functions that require multiple statements to return an object are known as multi-statement functions.

## Conclusion
This paper described how users can create functions to transform data. Scalar, inline, and multi-statement functions were also defined.
