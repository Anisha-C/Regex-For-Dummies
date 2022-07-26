# Title (replace with your title)

Introductory paragraph (replace this with your text)

## Summary

Briefly summarize the regex you will be describing and what you will explain. Include a code snippet of the regex. Replace this text with your summary.

/^([a-z0-9_\.-]+)@([\da-z\.-]+)\.([a-z\.]{2,6})$/

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
The components of a regex include: Anchors, Quantifers, Flags, Grouping and Capturing, and Boundaries.

### Anchors

The anchor is going to match the position in a string, an example of an anchor in my regex is at the beginning and end. ^ $

### Quantifiers
Quantififer is where an amount is depicted, the amount of a given capture / group. 
+ (one or more(needs to happen one or more times))
{2,6}(has to happen between 2 and 6 times)

### OR Operator

I don't have an OR operator but that would look like | 

### Character Classes
Anything that gets put inside [] ie a-z (all lower case if A-Z all upper) whichs ... 0-9 ...

### Flags
A flag comes at the end, and will dictate regex behavior.
for example i -> it will make things insenstive to the case of a character ie a-z and A-Z.
g = global (common) will find all matches in string

### Grouping and Capturing
() can be used to group things and the [] can also be used to capture specfic characters. 

### Bracket Expressions

[: some word :] this is the syntax for a bracket expression signifiying a special type of character depending what you insert.

### Greedy and Lazy Match

lazy mode enabled by puting ? after quantifyier repeat minimal number of times

### Boundaries

### Back-references

### Look-ahead and Look-behind

## Author

A short section about the author with a link to the author's GitHub profile (replace with your information and a link to your profile)
