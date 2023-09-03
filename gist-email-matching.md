# Gist Email Matching Tutorial

Regular expressions or Regex(shorthand), is a sequence of characters that define a specific search pattern. This tutorial will highlight and breakdown the expression of matching email addresses. 

## Summary

We will be diving into the following Regex to better understand how this expression helps match email addresses. 
Matching an Email – /^([a-z0-9_\.-]+)@([\da-z\.-]+)\.([a-z\.]{2,6})$/

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

A regex is considered a literal, so the pattern must be wrapped in slash characters (/). If we look at "Matching an Email Address" regex, you will notice that this is true:

/^([a-z0-9_\.-]+)@([\da-z\.-]+)\.([a-z\.]{2,6})$/

### Anchors

The starting anchor in this Regex is ^ this will always indicate the beginning of the string. The ending anchor for this Regex is $ this will always indicate the ending of the string.

### Quantifiers

Quantifiers are what tell the expression how many characters it needs to search for to make a match. Some of the common quantifiers in this expression are:

+ operator, which will connect the users email name + email service + .com

{2,6}, this will allow a match range of 2-6 characters for the character set of [a-z\.].


### Grouping Constructs

### Bracket Expressions

### Character Classes

### The OR Operator

### Flags

### Character Escapes

## Author

A short section about the author with a link to the author's GitHub profile (replace with your information and a link to your profile)
