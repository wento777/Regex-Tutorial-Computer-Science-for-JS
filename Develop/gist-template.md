# Regex Tutorial for Matching a URL

This Regex Tutorial explains about (Regex) and (url matching) and its going aver different Regex Components.

## Summary
Regular expressions, or regex for short, are a series of special characters that define a search pattern. This is the Regex for URL mtching: /^(https?:\/\/)?([\da-z\.-]+)\.([a-z\.]{2,6})([\/\w \.-]*)*\/?$/. This series of charachters might look like nonsense, but it's actually a search pattern meant for basic username validation.

## Table of Contents

- [Anchors](#anchors)
- [Quantifiers](#quantifiers)
- [OR Operator](#or-operator)
- [Character Classes](#character-classes)
- [Flags](#flags)
- [Grouping and Capturing](#grouping-and-capturing)
- [Bracket Expressions](#bracket-expressions)
- [Greedy and Lazy Match](#greedy-and-lazy-match)

## Regex Components

Components of a regex matching a URL include:

- Anchors ^ $
- Quantifiers * + ? {}
- OR Operator |
- Character classes \d \w .
- Flags -g  -i  -m
- Grouping and capturing ()
- Bracket expressions []
- Greedy match *




### * Anchors

The anchors characters are ^ and $. The ^ anchor signifies a string that begins with the characters that follow it. The $ anchor signifies a string that ends with the characters that precede it.



### * Quantifiers

Quantifiers set the limits of the string that your regex matches, they specify how many instances of a character or character group must be present in the input for a match to be found.




### * OR Operator

We use the OR operator (|) in this example (a|b|c) and it's not use in regex.



### * Character Classes

The character classes in regex defines a set of characters. This are the common character classes:
. matches any character, The character class \d matches a single character that is a digit, from 0 to 9. .—Matches any character except the newline character (\n).



### * Flags

Flags are placed at the end of regex, after the second slash, and they define additional functionality or limits for the regex. These flags can be used separately or together in any order, and are included as part of the regular expression.



### * Grouping and Capturing

Grouping constructs have two primary categories: capturing and non-capturing. Capturing groups capture the matched character sequences for possible re-use but non-capturing groups do not. There are 4 subexpression in capturing group( 1 (https?:\/\/)?,2 ([\da-z\.-]+),  3 ([a-z\.]{2,6}), 4 ([\/\w \.-]*)* )



### * Bracket Expressions

Brackets indicate a set of characters to match. The bracket metacharacter [] is a character set, and matches a string that has any character or combination of characters within the character set, for example, [jkl] matches a string that has a j, or j k, or jl. It is also the same as j|k|l, or [j-l].




### * Greedy and Lazy Match

The quantifier metacharacters * + and {} are greedy operators which expand the match as far as possible through the string. 
The URL regex uses the all of these metacharacters to quantify the number of matches of a particular string.

## Author

Andrei Florea

## * This project has been deployed to GitHub, here is the link:


- https://github.com/wento777/Regex-Tutorial-Computer-Science-for-JS/blob/main/README.md



- ANDREI FLOREA - Initial work - Git Hub Profile

- Challenge 17 | Computer Science for JavaScript Challenge: Regex Tutorial
