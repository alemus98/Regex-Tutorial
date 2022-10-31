# Regex Tutorial

Introductory paragraph (replace this with your text)

## Summary

JavaScript has tools to define search patterns for certain letter or phrases, however these tools can be limited to direct matches. Regex, or regular expressions can solve that by allowing for more dynamic and specific mathes. It does this by using a series of special characters to define a search pattern.

We'll be using this password regex `^(?=.*[A-Z])(?=.*[a-z]){10,}|(?=.*[A-Z])(?=.*[a-z])(?=.*[0-9])(?=.*[#?!@$%^&*-]){8,}$` to search for a password for our tutorial. It is searching for a password that contains at least one uppercase letter, one lowercase letter, a minimum length of 10 or contains at least one uppercase letter, one lowercase letter, a minimum length of 8 one number, one special character and be a minimum length of 8.


## Table of Contents

- [Anchors](#anchors)
- [Quantifiers](#quantifiers)
- [OR Operator](#or-operator)
- [Bracket Expressions](#bracket-expressions)
- [Flags](#flags)


## Regex Components

### Anchors
Anchors are what used to determine the start or of a search. The symbols "^" and "$" are both strings. 
In our example, 
- "^" signals the the start of the string 
- "$" signals the of the string.


### Quantifiers
Quantiifiers are what set the limits of the of the string that is being searched. Their main purpose of the find and include  the minumum and maximum amount of matches possible. 
in our example,
- "?" means that the search is being zere or one time.
- "*" means that the search is being matches 0 or more times.
- "{8,}" means that the search is being matches at least 8 times. 

### OR Operator
The OR opereator signals that either expression on both sides will be true.
In our example 
- The OR operator is signaled by the "|". So the string be either `(?=.*[A-Z])(?=.*[a-z]){10,}`  or  `(?=.*[A-Z])(?=.*[a-z])(?=.*[0-9])(?=.*[#?!@$%^&*-]){8,}`.
### Bracket Expressions
Character classes defines a set of characters which can fulfill a match. They are what is inside the square brackets "[]".
In our example
- 
- "[A-Z]" means that it is searching for a string with any uppercase letter from A-Z only.
- "[a-z]", means that is searching for a string with any lowercase letter from a-z only.
- "[0-9]", means that it is searching for a string that contains any number from 0-9.
- "[#?!@$%^&*-]" means that is is searching for a string that contains any of the special characters listed.

## Author

I'm a junior web developer from Los Angeles. (replace with your information and a link to your profile)

 Check out my work on [my github](https://github.com/alemus98)!