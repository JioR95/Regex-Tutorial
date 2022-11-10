# Regex Tutorial

In this tutorial will cover basic concepts for sequence of characters that forms a search pattern which referred as regular expressions

## Summary

Using regular expressions, you can perform advanced search patterns within strings of text. Matching patterns allow users to determine which patterns match the query and find them in any piece of text that they are targeting, replace them, and remove them from that piece of text.


## Table of Contents

- [Anchors](#anchors)
- [Quantifiers](#quantifiers)
- [OR Operator](#or-operator)
- [Character Classes](#character-classes)
- [Flags](#flags)
- [Grouping and Capturing](#grouping-and-capturing)
- [Bracket Expressions](#bracket-expressions)
- [Greedy and Lazy Match](#greedy-and-lazy-match)
- [Boundaries](#boundaries)
- [Back-references](#back-references)
- [Look-ahead and Look-behind](#look-ahead-and-look-behind)

## Regex Components

### Anchors

Anchors are a different breed, they are used in order to match a position before, after, or between characters. 

- ^ - is going to match begining of the string.
- $ - is goig to specify the end.

### Quantifiers

- * - Match zero times.
- *? - Match more times.
- + - Match one time
- +? - Match more times
- ? - Match zero
- ?? - Match more times

### OR Operator

 The vertical bar symbol | is used to seperate the multiple patterns that are being searched. 

### Character Classes

Set of characters that can occur a input for a match to suceed.

- \s: - is Whitespace
- \S: - is Not whitespace
- \w: - is Word 
- \s: - is Not word
- \d: - is Digit
- \D: - is Not digit
- \x: - is Hexade­cimal digit
- \O: - is Octal digit

### Flags

Regex has flags that may affect the search. Examples below:

- i - this flag the search is case-insensitive: no difference between A and a.

- g - With this flag the search looks for all matches, without it – only the first match is returned.

- m -  For multiline mode.

- s - It enables “dotall” mode, it allows a dot . to match newline character \n.

- u - This enables full Unicode support. This flag enables correct processing the surrogate pairs.

- y - This “Sticky” mode: searching at the exact position in the text.

### Grouping and Capturing

The subexpressions of a regular expression are distinguished by grouping structures, and the substrings of an input string are also captured. Example below:

- .: - Any character except newline (\n)
- (…): - Group
- (?:…): - Passive (non-capturing) group
- (a|b): - a or b
- [abc]: - a, b or c
- [^abc]: - Not a, b or c
- [a-z]: - Letters from a to z
- [A-Z]: - Uppercase letters from A to Z
- [0-9]: - Digits from 0 to 9 

### Bracket Expressions

- [] - Brackets show a set of charaters to match what ever. A single character inside the brackets will match.

- {} - Curly braces to show a exact amount of things to match.

### Greedy and Lazy Match

The difference between Greedy and Lazy is, Greedy quantifier will try to match the element repeatedly. As for Lazy it gives up first try.

### Boundaries

You can conduct a "whole words only" search with the \b metacharacter, as in \bword\b. You can define "not-word" boundaries using the \B metacharacter.

### Back-references

Back references are used to aggregate objects found in symbols and store a found value (which can be based on symbol \1 ).

### Look-ahead and Look-behind

Lookahead and lookbehind, also referred to as "lookaround," are zero-length statements, similar like the start and end of line and start and end of word anchors that were previously discussed in this tutorial. The key distinction is that lookaround really matches characters before giving up the match and just returns the match or no match outcome. They are called "assertions" for this reason. They just state if a match is possible or not; they do not actually take characters out of the string. Regular expressions that are either impossible to build without Lookaround or would be extremely laborious to construct without it can be created with it.

## Author

Name is Jiovani Rivera working my way to becoming your friendly neigborhood developer.

link to my github "https://github.com/JioR95"
