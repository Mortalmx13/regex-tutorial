# Title (Matching an Email)

Introductory paragraph (replace this with your text)

## Summary

Regex is simular to a regualar expression but in this case that it helps create a search patterns that will help match and locate certain text.

Code Example: /^([a-z0-9_\.-]+)@([\da-z\.-]+)\.([a-z\.]{2,6})$/

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

* ^ means that it must be the start of the string.

* $ means that the code that was written before this symbol is at the end of the string.

### Quantifiers

In this case the regex uses two quantifiers, `{2,6}` and `+`.

* `+` matches a string that has the anterior followed by one or more of the last character.  

* In this case the `{2,6}` means the component that was previous to this should be a lenth between 2 and 6 characters.

### Grouping Constructs

* grouping is done by `()` in regex

* In tis case there are three different instances of this `([a-z0-9_\.-]+)` , `([\da-z\.-]+)` and `([a-z\.]{2,6})`

### Bracket Expressions

* Bracket expression is represented by one character []. This is used to specify what character belongs at that position.

* There is 3 in this example `[a-z0-9_\.-]` , `[\da-z\.-]` and `[a-z\.]`

### Character Classes

* In this case character classes only happen one and that is `\d`.

* What this does is allows there to be digets in the list of characters. 

### The OR Operator

* In this case it is not being used.

* This is used by using the characters `|` and `[]`.

* This is used as an or character, for example `([a-f0-9]{6}|[a-f0-9]{3})` the `|` is saying that it can be either 6 or 3 characters.

### Flags

* flags are parameters that can be used to seach in different ways depending on the character.


* `g` - Global, searches for all occurences and doesnt return after the first occurence.
* `m` - Multi-line, when applied the Anchors will indicate the end of the line.
* `i` - Insensitive, make the expression case-insensitive

### Character Escapes

* In this case ther are 5 different cases of this but some repeat the same thing.

Examples: 
 - - `\.`
 - - `\d `

* In the case of the `\.` it measn two different things in this line of code. It could eather mean that there always has to be a (.) in the thing they are searching for or in the other case it could posible use it in the list of characters.

* The  `\d` character escape represents any number 0-9


## Author
Charles Young
https://github.com/Mortalmx13