# Regex Tutorial
Validation using Regular Expression
## Summary

The regular expression we'll be examining is:

^[\w\.-]+@[a-zA-Z\d\.-]+\.[a-zA-Z]{2,}$


## Table of Contents

- [Anchors](#anchors)
- [Quantifiers](#quantifiers)
- [Character Classes](#character-classes)
- [Grouping and Capturing](#grouping-and-capturing)
- [Bracket Expressions](#bracket-expressions)

## Regex Components

### Anchors
Anchors are special characters that assert a position at the start or end of a line.
^    # Asserts the start of a line
$    # Asserts the end of a line


### Quantifiers
Quantifiers specify how many instances of a character or group should be matched.
+    # Matches one or more of the preceding element
{2,} # Matches two or more of the preceding element

### Character Classes
Character classes match any one of a set of characters.
\w    # Matches any word character (alphanumeric + underscore)
\d    # Matches any digit
.     # Matches any character except a newline

### Grouping and Capturing
Parentheses are used for grouping and capturing parts of a regular expression.
(ab)+    # Matches "ab", "abab", "ababab", etc.
(a|b)    # Matches "a" or "b"

### Bracket Expressions
Bracket expressions match any one of a set of characters enclosed in square brackets.
[a-zA-Z]   # Matches any uppercase or lowercase letter
[0-9]      # Matches any digit
[^a-z]     # Matches any character that is not a lowercase letter

## Author
This tutorial was written by Lee Amick

[GitHub - LeeAmick](https://github.com/LeeAmick)
