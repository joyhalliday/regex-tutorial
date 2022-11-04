# Regex Tutorial: Matching an Email

Regular expressions, or regex for short, are a series of special characters that define a search pattern. They may appear inscrutable if you do not know how to read them, but are a good way to create a search pattern. Once you learn to read a recoginize the search pattern, they become much easier to read. 

## Summary

Matching an Email: `/^([a-z0-9_\.-]+)@([\da-z\.-]+)\.([a-z\.]{2,6})$/`

This tutorial will cover using regular expressions in order to match to an email address. The above code is an example of a regex that would define a search pattern for an email address.

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

Required in all regex match types, the expression will be wrapped in slash characters (/)

### Anchors

The characters (^) and ($) are both considered to be anchors.

The use of the (^) signifies the start of the search characters.

The use of ($) signifies the end of the search characters. 

### Quantifiers

### Grouping Constructs

### Bracket Expressions

Anything inside a set of square brackets ([]) represents a range of characters that we want to match. 
[a-z0-9_\.-]- this signifies to expect all letters of the alphabet, numbers 0 through 9, as well as the symbols (_), (\), (.), (-). This section will contain the expected values for the first part of the user's email.
[\da-z\.-]
[a-z\.]

### Character Classes

### The OR Operator

Not applicable to this regex.

### Flags

Not applicable to this regex. 

### Character Escapes

## Author

Joy Halliday 
https://github.com/joyhalliday
