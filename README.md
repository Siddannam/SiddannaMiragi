# README - Java Problem Solutions

This project contains Java solutions for four programming problems:
## Problem 1: Calculator using Class
A simple calculator that performs:

* Addition
* Subtraction
* Multiplication
* Division

**Inputs:**

* `b` (double)
* `operation` (String): one of "add", "subtract", "multiply", or "divide"

**Usage:**

java
Calculator calc = new Calculator(10, 5, "add");
System.out.println("Result: " + calc.calculate());


## Problem 2: Print Odd Numbers up to 'a'

Prints the first `a` odd numbers in sequence.

**Input:**

* `a` (int): number of odd numbers to print

**Example:**

* Input: 4 → Output: 1, 3, 5, 7

## Problem 3: Custom Odd Number Sequence

Prints odd numbers until index `a`, but behaves as:

* If `a` is odd: print first `a` odd numbers
* If `a` is even: print first `a-1` odd numbers

**Example:**
* Input: 6 → Output: 1, 3, 5, 7, 9

## Problem 4: Count Multiples
Counts how many numbers in the list are divisible by each of 1 through 9.
**Input:**
* A list of integers
**Example:**
* Input: `[1,2,8,9,12,46,76,82,15,20,30]`
* Output:
{1=11, 2=8, 3=4, 4=4, 5=3, 6=2, 7=0, 8=1, 9=1}
## How to Compile and Run
1. Save the code in a file named `Main.java`
2. Open terminal or command prompt
3. Compile:
javac Main.java
4. Run:
java Main


