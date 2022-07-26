# 1.1 The Elements of Programming
Every language has 3 mechanisms for accomplishing complex ideas
* primitive expressions: represents simple entities the language is concerned with
* means of combiniation: by which compound elements are built from simpler ones
* means of abstraction: by which compound elements can be named and manipulated as units

## 1.1.1 Expressions
* operator, operand, arguments, nested combinations, prefix notation

## 1.1.2 Naming and the Environment
* memory is env, can have multiple env (scope)

## 1.1.3 Evaluating Combinations
* tree accumulation, special forms (define)

## 1.1.4 Compound Procedures
* Procedure Definitions, compound procedure (function)
* (define (<name> <formal parameters>) <body>)

## 1.1.5 The substitution Model for Procedure Application
* substitution model, normal order model, way of thinking about how things evaluate

## 1.1.6 Conditional Expressions and Predicates
* Case analysis, predicate

## 1.1.7+
* Procedural abstraction, local name(local var)
* block structure, lexical scoping


# 1.2 Procedures and the Processes they Generate

## 1.2.1
* Deferred operations (recursive process)
* Linear recursive process
* iteravie process, state variables, linear iterative process
* inc (+ 3 5)

## 1.2.2 Tree Recursion
* 

fib 5
fib-iter 1 0 5

fib-iter (+ 1 0) 1 4
fib-iter (+ 1 1) 1 3
fib iter (+ 2 1) 2 2

## 1.2.3 Orders of Growth
* order of growth to obtain a gross measure of the resources required by a process as the inputs become larger

## 1.2.4 Exponentiation 
* Euclid's Algorithm
* Square