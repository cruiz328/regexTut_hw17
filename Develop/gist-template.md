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
Quantifiers include the '+' sign, which connects the users email name along with the users email service name, also using the '.com' in said regex. '{a-z}' are other quantifiers that say that the 'whole alphabet' is able to be used.


### OR Operator
N/A
### Character Classes
'{/d}' is used to say that numbers/digits '0-9' or 'all of the digits used as a single/lone digit' are able to be used in said regex. '22' won't be read, but '2' will be. 

### Flags
N/A
### Grouping and Capturing
In the regex expression show above in the example used in the [Summary](#summary) ' /^[a-zA-Z0-9.!#$%&’*+/=?^_`{|}~-]+ ', this is used to match the user email or the 'useremail("username")'  of an email. 
The second half of the regex code, ' @[a-zA-Z0-9-]+ ' or the '@usermail' is used to match the service provider for the users email address. 
The third half of the regex expression is ' (?:\.[a-zA-Z0-9-]+)*$/ ' or the '.com' portion and this simply caputers the .com of the email address.

### Bracket Expressions

### Greedy and Lazy Match

### Boundaries

### Back-references

### Look-ahead and Look-behind

## Author

A short section about the author with a link to the author's GitHub profile (replace with your information and a link to your profile)
