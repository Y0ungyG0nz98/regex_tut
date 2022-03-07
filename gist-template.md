# Title What is REGEX

Regex is an abbreviation for Regular Expressions. It's a pattern of values such as: numbers, letters, and unique signs that describe a text

## Summary

^[a-z0-9]{7-10}$ is an example of a regular expression that is used to describe the parameters of whatever input it's attatched to. What this will describe are the individual characteristics of a regular expression in each table.

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

### The components of Regex include:
    - Matching Fixed Strings
    - Matching Special Characters
    - Matching Character Sets
    - Specifying Groups and Fields
    - Evaluating Occurrences
    - Specifying Location
    - Specifying Alternatives
    - Matching Information from a Table
    - Capturing Multiple Lines
    - Managing the Scope of Analysis

### Anchors

    ^[a-z0-9]{7-10}$
    In this example of a Regular Expression, the ^ is the position of the first character of a regular expression. Whereas the $ is the last character of a line

### Quantifiers

    Quantifiers are used to specifiy how many instances of a character group or class must be present in the input for a match to be found.

    Includes:
        - *         Match zero or more times
        - +         Match one or more times
        - ?         Match zero or one time
        - { n }     Match exactly n times
        - { n, }    Match at least n times
        - { n, m }  Match from n to m times

### Grouping Constructs

    Grouping Constructs delineate the subexpressions of a regular expression and capture the substrings of an input string.

    Grouping construct:	                             Capturing or noncapturing:

    Matched subexpressions	                     |   Capturing
    Named matched subexpressions	             |   Capturing
    Balancing group definitions	                 |   Capturing
    Noncapturing groups	                         |   Noncapturing
    Group options	                             |   Noncapturing
    Zero-width positive lookahead assertions	 |   Noncapturing
    Zero-width negative lookahead assertions	 |   Noncapturing
    Zero-width positive lookbehind assertions	 |   Noncapturing
    Zero-width negative lookbehind assertions	 |   Noncapturing
    Atomic groups                                |   Noncapturing

### Bracket Expressions

    A Bracket Expression is either a matching or a non-matching list expression. 
    It consists of:
        - Ordinary Characters
        - Collating Elements
        - Collating Symbols
        - Equivalence Classes
        - Character Classes
        - Range Expressions

### Character Classes

    Expressed as a character class name enclosed in within <>

    Used to match only one single character out of several characters. 

### The OR Operator



### Flags

### Character Escapes

## Author

    https://github.com/Y0ungyG0nz98

