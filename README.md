# CSC-122-Wk1
<s>Password Validation assignment</s>
Hello==hello assignment
## Problem Statement
Your goal for this lab is to implement a function that compares two strings (lexicographically). 
However, it should be case insensitive. That is, the letter 'A' is considered equal to the letter 'a'. 
Remember that a lexicographic ordering is a generalization of an alphabetical ordering, such that things are ordered based on comparing their individual elements,-
-one at a time until a non-match is found. 
Remember that a string may have non-alphabetical characters, you should support those as well. 
For this, remember that characters have an ordering given to them by the ASCII standard, and this ordering is what is used by the built-in comparison operators.

Given an input of two strings, your function should:
-Return a negative number if string1 is less than string2
-Return zero if the strings are equivalent
-Return a positive number if string1 is greater than string2

If one string is shorter than the other, but all the characters it has match, it should be considered less than the longer string. E.g. "app" < "apple"
This mirrors the return type of the (case sensitive) standard library function, strcmp. You may not use this function, or any similar variants.

Use assert() to write unit tests for your function.
