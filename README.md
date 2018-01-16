# Python-Exercises-1
Set of 3 Python Exercises and Accompanying Test Cases

1. Monte Carlo Simulation Estimation of Pi

Given a parameter "digits," uses Monte Carlo Simulation to estimate Pi to that number of decimal places. For sake of efficiency, 0 <= digits <= 6.


2. Naive Solution to Simple Substitution Cipher using Frequency Analysis

Partial solution to solving a simple substitution cipher using frequencies. Given a long input text of uppercase letters with all spaces removed, returns decoded version of text.


3. Implementation of a Tokenizer and Parser for Mathematical Expressions, 

Returns evaluated simple expression if exp is formatted correctly, else returns -1

A simple expression is a string that is either a non-negative integer i = "i" with no leading zeroes

or in the form "( exp1 op exp2 )" where exp1 and exp2 are valid simple expressions and op is either +, -, *, or /

i.e. valid = "42" "( 5 + 3 )" "( ( 728 - ( 10 + 2 ) ) * ( 10 - 6 ) )"

i.e. invalid = 42 "(5+3)" "003" "44.5" "-3" "( 40 / 0 )" "( 10 + 2 ) * 5"
