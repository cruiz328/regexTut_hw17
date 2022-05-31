# The thing about matching an email (regex tutorial)

today i'll be explaining the thing about regex pattern and matching an email using 
' const emailRegex = RegExp(
    /^[a-zA-Z0-9.!#$%&’*+/=?^_`{|}~-]+@[a-zA-Z0-9-]+(?:\.[a-zA-Z0-9-]+)*$/
  ); '

## Summary

this expression is a sequence of characters usually used to search for a string that match a certain pattern. Simple or complex, if its in the set of rules, then the pattern will be found.

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
For regex expressions used to match an email, the anchors used are '^', 
which means that the  beginning and ending of the string. Since 'multiline' isn't enabled, this regex
ends at '$'
### Quantifiers
Quantifiers include the '+' sign, which connects the users email name along with the users email service name, also using the '.com' in said regex. '{a-z/d/-}' are other quantifiers that say that the 'whole alphabet' is able to be used and also that all 'digits' can be used and 'hyphons' can be used as well.

### OR Operator

### Character Classes

### Flags

### Grouping and Capturing

### Bracket Expressions

### Greedy and Lazy Match

### Boundaries

### Back-references

### Look-ahead and Look-behind

## Author

A short section about the author with a link to the author's GitHub profile (replace with your information and a link to your profile)
