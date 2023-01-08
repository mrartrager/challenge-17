# Computer Science Hex Regex Tutorial and functionality 

Hello, I am making this tutorial so that I can hopefully help someone down the road understand the very thing I was confused about. Even though this is a homework assignment I am actually loving the idea that this could help someone else. 


## Summary

I picked the Hex Regex to explain because as I work through this coarse, to no surprise, I am loving the front end aspect of coding. Out of all the options given to choose from for this assignment, matching a Hex value with a regex seemed the most useful for me to know about, especially for the front end aspect of things.

Here is the Regex (Regular Expression) That I will be going in detail about:  

/^([a-z0-9_\.-]+)@([\da-z\.-]+)\.([a-z\.]{2,6})$/


## Table of Contents

- [Anchors](#anchors)
- [Quantifiers](#quantifiers)
- [OR Operator](#or-operator)
- [Character Classes](#character-classes)
- [Grouping and Capturing](#grouping-and-capturing)
- [Bracket Expressions](#bracket-expressions)
- [Greedy and Lazy Match](#greedy-and-lazy-match)


## Regex Components

Everything below goes into and breakers down all the components of a Hex Value Regex. Let’s start with the anchors. 

### Anchors

Anchors of a regex are to show the start and the end of a string, so for example in the hex regex listed above, the anchors would be ^ and $. 

The ^ indicates the start of the string 
The $ indicates the end of the string
Note: The / at the beginning and end of the regex indicate the start and end of the regex, not the string.


### Quantifiers

Quantifiers are pretty much what they sound like. But I won't be that person that describes a word, using the word you’re trying to understand. Quantifiers pretty much show how many times the following pattern matches. 

### OR Operator

The OR Operator of regex is a pretty simple concept to understand. The OR Operator can be found  in { } in the Regex expression. For the one provided our OR Operator would be the: {2, 6} found towards the end of the expression. 

This allows the OR Operator to match a  hex value that has either a 2 or a 6 in it.  

### Character Classes

In my opinion character classes and bracket expressions are very silimair, You’ll learn about bracket expressions soon. Character classes and essentially the parameters of what will be matched with your regex. So for example our is: a-z0-9_\.-

This is saying our regex will have any lowercase (because its a-z it’s literally searching for the entire alphabet, you could do a-g and that would show any hex value with letters a-g) and then any number 0-9. Again if you wanted a more narrow search you can shrink the distance between values so just as I said instead of searching through the entire alphabet, you could just search for numbers 1-4. 




### Flags

### Grouping and Capturing

### Bracket Expressions

### Greedy and Lazy Match

### Boundaries

### Back-references

### Look-ahead and Look-behind

## Author

A short section about the author with a link to the author's GitHub profile (replace with your information and a link to your profile)