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

The + operator, which will connect the users email name + email service + .com.

{2,6}, this will allow a match range of 2-6 characters for the character set of [a-z\.].


### Grouping Constructs

() are used in this expression to capture groupings of code and make them work together. Some of these were mentioned in the quantifiers.

1st group ([a-z0-9_\.-]+)

2nd group ([\da-z\.-]+)

3rd group ([a-z\.]{2,6})

This grouping system allows us to easily see the code and break it into the parts for the email.

### Bracket Expressions

Bracket expressions for this Regex include the character sets of [a-z0-9_\.-], which is matching any letter a-z and is case sensitive. It also matches a character 0-9 and matches the characters "_", "-", and "." as seen in the 3 groups above.

### Character Classes

These are used to show what characters you want to include in your match. These are always shown inside the brackets. This expression shows character sets three different times. 

1st a-z0-9_\.- This shows that they want to include any lowercase letter from a to z and any digit from 0 to 9. The backslash shows that we want to use the literal symbol meaning we also want to include the underscore (\_), a period (.), and a dash (-).

2nd \da-z\.- The \d represents any number from 0-9. The a-z means we want to include all lowercase letters a through z. The backslash shows we want to use the literal characters for period(.) and dash(-).

3rd a-z\. This includes any lowercase letter from a to z. The backslash is again showing we want to use the literal period (.).

### The OR Operator

### Flags

### Character Escapes

## Author

A short section about the author with a link to the author's GitHub profile (replace with your information and a link to your profile)
