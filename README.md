# MegaProjectList
Guide to an assortment of practical programs as part of a project challenge.

This repo is a collection of implementations of the project ideas suggested by [Karen Goel](https://github.com/karan/Projects) from which this repo was forked. Please visit the original repo to create your own solutions and see those created by other users.

The full original list can be found in the original repo. As I complete more programs from the list, I will add them to this list.

## Table of Contents

- [Numbers](https://github.com/the-handsome-monkey-king/MegaProjectList#numbers)
- [Classic Algorithms](https://github.com/the-handsome-monkey-king/MegaProjectList#classic-algorithms)
- [Graph](https://github.com/the-handsome-monkey-king/MegaProjectList#graph)

Numbers
---------

**Find e to the Nth Digit** - Enter a number and have the program generate e up to that many decimal places. Keep a limit to how far the program will go. 
- [python](https://github.com/the-handsome-monkey-king/find_euler.py)
- [python (spigot)](https://github.com/the-handsome-monkey-king/euler_spigot.py)
- [c](https://github.com/the-handsome-monkey-king/euler_spigot.c)
- [c++](https://github.com/the-handsome-monkey-king/euler_spigot.cpp)

**Fibonacci Sequence** - Enter a number and have the program generate the Fibonacci sequence to that number or to the Nth number. 
- [python](https://github.com/the-handsome-monkey-king/fibonacci.py)
- [c](https://github.com/the-handsome-monkey-king/fibonacci.c)
- [c++](https://github.com/the-handsome-monkey-king/fibonacci.cpp)

**Prime Factorization** - Have the user enter a number and find all Prime Factors (if there are any) and display them. 
- [python](https://github.com/the-handsome-monkey-king/prime_factors.py)
- [c](https://github.com/the-handsome-monkey-king/prime_factors.c)
- [c++](https://github.com/the-handsome-monkey-king/prime_factors.cpp)

**Next Prime Number** - Have the program find prime numbers until the user chooses to stop asking for the next one. 
- [python](https://github.com/the-handsome-monkey-king/next_prime.py)
- [c](https://github.com/the-handsome-monkey-king/next_prime.c)
- [c++](https://github.com/the-handsome-monkey-king/next_prime.cpp)

**Find Cost of Tile to Cover W x H Floor** - Calculate the total cost of tile it would take to cover a floor plan of width and height, using a cost entered by the user. 
- [python](https://github.com/the-handsome-monkey-king/get_tile_cost.py)
- [c](https://github.com/the-handsome-monkey-king/get_tile_cost.c)
- [c++](https://github.com/the-handsome-monkey-king/TileEstimator.cpp)

**Mortgage Calculator** - Calculate the monthly payments of a fixed term mortgage over given Nth terms at a given interest rate. Also figure out how long it will take the user to pay back the loan. For added complexity, add an option for users to select the compounding interval (Monthly, Weekly, Daily, Continually). 
- [python](https://github.com/the-handsome-monkey-king/mortgage.py)
- [c](https://github.com/the-handsome-monkey-king/mortgage.c)
- [c++](https://github.com/the-handsome-monkey-king/MortgageCalculator.cpp)

**Change Return Program** - The user enters a cost and then the amount of money given. The program will figure out the change and the number of quarters, dimes, nickels, pennies needed for the change. 
- [python](https://github.com/the-handsome-monkey-king/change_return.py)
- [c](https://github.com/the-handsome-monkey-king/change_return.c)
- [c++](https://github.com/the-handsome-monkey-king/ChangeCalculator.cpp)

**Binary to Decimal and Back Converter** - Develop a converter to convert a decimal number to binary or a binary number to its decimal equivalent. 
- [python](https://github.com/the-handsome-monkey-king/binary_to_decimal.py)
- [c](https://github.com/the-handsome-monkey-king/decimal_to_binary.c)
- [c++](https://github.com/the-handsome-monkey-king/BinaryConverter.cpp)

**Calculator** - A simple calculator to do basic operators. 
- [python](https://github.com/the-handsome-monkey-king/simple_calculator.py)
- [c](https://github.com/the-handsome-monkey-king/simple_calculator.c)
- [c++](https://github.com/the-handsome-monkey-king/SimpleCalc.cpp)

**Unit Converter (temp, currency, volume, mass and more)** - Converts various units between one another. The user enters the type of unit being entered, the type of unit they want to convert to and then the value. The program will then make the conversion. 
- [python](https://github.com/the-handsome-monkey-king/unit_converter.py)
- [c](https://github.com/the-handsome-monkey-king/unit_converter.c)

**Credit Card Validator** - Takes in a credit card number from a common credit card vendor (Visa, MasterCard, American Express, Discoverer) and validates it to make sure that it is a valid number (look into how credit cards use a checksum). 
- [python](https://github.com/the-handsome-monkey-king/verify_credit_card.py)
- [c++](https://github.com/the-handsome-monkey-king/verify_credit_card.cpp)

**Tax Calculator** - Asks the user to enter a cost and either a country or state tax. It then returns the tax plus the total cost with tax. 
- [python](https://github.com/the-handsome-monkey-king/sales_tax.py)
- [c++](https://github.com/the-handsome-monkey-king/Tax.cpp)

**Factorial Finder** - The Factorial of a positive integer, n, is defined as the product of the sequence n, n-1, n-2, ...1 and the factorial of zero, 0, is defined as being 1. Solve this using both loops and recursion. 
- [python](https://github.com/the-handsome-monkey-king/factorial_finder.py)

**Complex Number Algebra** - Show addition, multiplication, negation, and inversion of complex numbers in separate functions. (Subtraction and division operations can be made with pairs of these operations.) Print the results for each operation tested. 
- [python](https://github.com/the-handsome-monkey-king/complex_numbers.py)

**Happy Numbers** - A happy number is defined by the following process. Starting with any positive integer, replace the number by the sum of the squares of its digits, and repeat the process until the number equals 1 (where it will stay), or it loops endlessly in a cycle which does not include 1. Those numbers for which this process ends in 1 are happy numbers, while those that do not end in 1 are unhappy numbers. Display an example of your output here. Find first 10 happy numbers. 
- [python](https://github.com/the-handsome-monkey-king/happy_numbers.py)

**Number Names** - Show how to spell out a number in English. You can use a preexisting implementation or roll your own, but you should support inputs up to at least one million (or the maximum value of your language's default bounded integer type, if that's less). *Optional: Support for inputs other than positive integers (like zero, negative integers, and floating-point numbers).* 
- [python](https://github.com/the-handsome-monkey-king/number_names.py)

**Coin Flip Simulation** - Write some code that simulates flipping a single coin however many times the user decides. The code should record the outcomes and count the number of tails and heads. 
- [python](https://github.com/the-handsome-monkey-king/coin_flips.py)

**Fast Exponentiation** - Ask the user to enter 2 integers a and b and output a^b (i.e. pow(a,b)) in O(lg n) time complexity. 
- [python](https://github.com/the-handsome-monkey-king/fast_exp.py)

Classic Algorithms
-----------------

**Collatz Conjecture** - Start with a number *n > 1*. Find the number of steps it takes to reach one using the following process: If *n* is even, divide it by 2. If *n* is odd, multiply it by 3 and add 1.
- [python](https://github.com/the-handsome-monkey-king/collatz_conjecture.py)

**Sorting** - Implement two types of sorting algorithms: Merge sort and bubble sort.
- [bubble sort - python](https://github.com/the-handsome-monkey-king/bubble_sort.py)
- [merge sort - python](https://github.com/the-handsome-monkey-king/merge_sort.py)

**Closest pair problem** - The closest pair of points problem or closest pair problem is a problem of computational geometry: given *n* points in metric space, find a pair of points with the smallest distance between them.
- [python](https://github.com/the-handsome-monkey-king/closest_pair.py)

**Sieve of Eratosthenes** - The sieve of Eratosthenes is one of the most efficient ways to find all of the smaller primes (below 10 million or so).
- [python](https://github.com/the-handsome-monkey-king/sieve_of_eratosthenes.py)

Graph
------

**Graph from links** - Create a program that will create a graph or network from a series of links.
- [python](https://github.com/the-handsome-monkey-king/Network.py)

**Eulerian Path** - Create a program which will take as an input a graph and output either a Eulerian path or a Eulerian cycle, or state that it is not possible. A Eulerian Path starts at one node and traverses every edge of a graph through every node and finishes at another node. A Eulerian cycle is a eulerian Path that starts and finishes at the same node.
- [python](https://github.com/the-handsome-monkey-king/Network.py)

**Connected Graph** - Create a program which takes a graph as an input and outputs whether every node is connected or not.
- [python](https://github.com/the-handsome-monkey-king/Network.py)
