# Let me walk you through the way of Regex! 

Below is an explanation on how to match an email using REGEX. 

## Summary

What is Regex? Regex, also known as Regular Expression, is a way of searching a database/set/text and specifically going through it to find what it wants. Almost like using a filter. It can find, or even find and replace key concepts on a string or an input. This type of algorithm search makes it easier for developers and users to get the information they need. 

Matching an email example code – /^([a-z0-9_\.-]+)@([\da-z\.-]+)\.([a-z\.]{2,6})$/


## Table of Contents

- [Anchors](#anchors)
- [Quantifiers](#quantifiers)
- [OR Operator](#or-operator)
- [Character Classes](#character-classes)
- [Flags](#flags)
- [Grouping and Capturing](#grouping-and-capturing)
- [Bracket Expressions](#bracket-expressions)
- [Greedy and Lazy Match](#greedy-and-lazy-match)
- [Boundaries](#boundaries)
- [Back-references](#back-references)
- [Look-ahead and Look-behind](#look-ahead-and-look-behind)

## Regex Components

### Anchors
There are everal Anchors within this code, because of that, here are a few explanations of what they are and what they do.
^ = it's the beginning of the string or line
$ = it's the end of the string or line

### Quantifiers
{} = indicates the number of characters, expressions, and etc that could be a match. Example being used is {2,6} towards the end of the line. It means it could be between 2-6 characters. 

+ = tells machine to match the quantitiy to the character left of it. 

### OR Operator
N/A

### Character Classes
[] = are used to find specific letters/numbers/keys that are needed/searched for in a set. 
    Example: you can't recall the exact spelling of a name but know it may be of two options, you can use e or i to locate it. Bustam*i* or Bustam*e* when the true spelling is Bustami, so you can use [ei] or [ie] to search. Either way, it will bring you the true result. 

- = sets a range between letters, number, etc. 

### Flags
N/A

### Grouping and Capturing
() = captures an expression and separates them

### Bracket Expressions
In this example of code, [a-z] means letters from a to z and [0-9] are numbers between 0 to 9. 

### Greedy and Lazy Match
Greedy = is matching/getting the longest string
Lazy = is matching/getting the shortest string


### Boundaries
N/A

### Back-references
N/A

### Look-ahead and Look-behind
N/A 

## Author

Yasmin Bustami - repo : https://github.com/yazbustami/Challenge17
gist: https://github.com/yazbustami/Challenge17/blob/main/Develop/gist-template.md
