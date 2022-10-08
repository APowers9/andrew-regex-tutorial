# Matching an Hex Value with Regex

This is a tutorial that will teach you the different parts of a regex so you can use it to match hex values 

## Summary

I will be breaking down the different parts of a regex so you can make sense of how a hex value regex: /^#?([a-f0-9]{6}|[a-f0-9]{3})$/

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
  Anchors are either ^ or \$. ^ is used to signify a string that contains the characters proceeding it. \$ is used to signify a string with characters that preceed it.
### Quantifiers
  Quantifiers allow you to be more strict in how you search for a match, the following is a list of quantifiers: \*, \+, ?, { }, { n }, { n, }, and { n, x }. \* 
### Grouping Constructs
  Grouping constructs let you segment parts of your string into groups. you can do this by putting characters in parentheses and putting a colon in between them. Ex : (abc):(123).
### Bracket Expressions
  Bracket expressions allow you to set a range of characters, for example: \[A-Z] would represent the entire aplhabet capitalized and \[a-z] would be the alphabet without capitalization.
### Character Classes
  Character classes shows what kind of character you're using. . is pretty much all-encompassing, \d is for numbers, and \w is for letters
### The OR Operator
  The OR operator | allows you to take a string and match characters to the left and right of it, similar to grouping constructs
### Flags
  Flags are placed at the end of the regex all the way to the right, and it decides how to search. g is global search, i is case-insensitive search, and m is multi-line search. 
### Character Escapes
Similar to writing special characters in markdown, character escapes in regex remove the "effect" from a character that would otherwise have a different use, example: \[normal brackets]
## Author
[Github Repository](https://github.com/APowers9)