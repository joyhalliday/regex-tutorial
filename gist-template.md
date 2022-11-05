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

Quantifiers exist outside of the brackets and exist as limits for the string.

(+) Matches the pattern one or more times
For this example, the plus signifies that the characters within the brackets on either side of the (@) symbol in the email

({}) Provide ways to set limits
For this example, it expects the preceeding string to be between 2 and 6 matchng characters in length and will expect the final part of the email address (.com, .net, etc)

### Grouping Constructs

Not applicable to this regex.

### Bracket Expressions

Anything inside a set of square brackets ([]) represents a range of characters that we want to match. 
[a-z0-9_\.-]- this signifies to expect all letters of the alphabet, numbers 0 through 9, as well as the symbols (_), (.), (-). This section will contain the expected values for the first part of the user's email.
[\da-z\.-]
[a-z\.]

### Character Classes

Ths defines a set of characters which can be used to create an input match. 

For example, in the expression [\da-z\.-], the (\d) is used as a shorthand to include numbers 0-9 while using up less space in the expression.

### The OR Operator

Not applicable to this regex.

### Flags

Not applicable to this regex. 

### Character Escapes

Makes use of the (\) character to signify that the following character should not be used literally. 

## Author

Joy Halliday 
https://github.com/joyhalliday
