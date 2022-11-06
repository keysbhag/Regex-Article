# Regex Expression Email

The term Regex stands for 'Regular Expression' and is used as pattern to match inputs of string to our specific needs. It is mainly used to make sure that a text inputted by a user matches the criteria that a developer set for that input.

## Summary

Briefly summarize the regex you will be describing and what you will explain. Include a code snippet of the regex. Replace this text with your summary.

In this specific tutorial I will be explaining how the regex pattern for the email validator works. If you take a look at the code snippet below, you will see what a typical email regex statement will look like.
```md
/^([a-zA-z0-9_\.-]+)@([\da-zA-Z\.-]+)\.([a-z\.]{2,6})$/
```
To briefly summarize what is going on here, all the character before the @ symbol in the snippet above which looks like
```md
/^([a-zA-z0-9_\.-]+)
```
Represents the accepted string of input that a user can add before the @ symbol of an email which in this case is set in between the square brackets. the user can have letters that are a-z in lower case, A-Z upper case, 0-9 and allows for underscores, periods, and dashes.
```md
([\da-z\.-]+)
``` 
This next line represents what allowed character are to be entered in between the @ symbol and period, which is any digit from 0-9, uppercase and lowercase a-z, a period and a dash
```md
\.([a-z\.]{2,6})$/
```
The final sequence is anything after the period which can be lowercase a-z, and has to be between 2 and 6 characters in length

## Table of Contents

- [Anchors](#anchors)
- [Quantifiers](#quantifiers)
- [Grouping Constructs](#grouping-constructs)
- [Bracket Expressions](#bracket-expressions)
- [Character Classes](#character-classes)
- [The OR Operator](#the-or-operator)
- [Flags](#flags)
- [Character Escapes](#character-escapes)

## Regex Components

### Anchors

### Quantifiers

### Grouping Constructs

### Bracket Expressions

### Character Classes

### The OR Operator

### Flags

### Character Escapes

## Author

A short section about the author with a link to the author's GitHub profile (replace with your information and a link to your profile)