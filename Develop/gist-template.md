# Regex Tutorial
The challenge this week is to create a tutorial that explains how a specific regular expression, or regex, functions by breaking down each part 
of the expression and describing what it does.A regex, which is short for regular expression, is a sequence of characters that defines a specific search pattern. When included in code or search algorithms, regular expressions can be used to find certain patterns of characters within a string, or to find and replace a character or sequence of characters within a string. They are also frequently used to validate input.

For example, the following regular expression can be used to verify that user input is a valid email address:

/^([a-z0-9_\.-]+)@([\da-z\.-]+)\.([a-z\.]{2,6})$/

Each component of this regex has a unique responsibility to make sure that a user enters an email address that begins with an unspecified number of characters preceding the @ symbol, followed by a domain.

## Summary
AS A web development student
I WANT a tutorial explaining a specific regex
SO THAT I can understand the search pattern the regex defines

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
Anchors are special characters that represent positions in the input string. (^, $, \b, and \B)

### Quantifiers
Quantifiers allow us to specify how many times a character or a group of characters can appear in a match. (*,+ , ?, {})

### OR Operator
The OR Operator| is used to match either of the patterns separated by it.

### Character Classes
Character classes provide a way to match any one of a set of characters.

### Flags
Flags are modifiers that can be added to the end of a regex pattern to change how the pattern is interpreted or applied.

### Grouping and Capturing
Grouping allows us to treat multiple characters as a single unit. You can learn how to explore the use of () for grouping and capturing substrings.

### Bracket Expressions
Allow you to specify a set of characters that you want to match. They are enclosed within square brackets [ ]. For example, [aeiou] matches any single vowel character (a, e, i, o, or u).

### Greedy and Lazy Match
In regular expressions, quantifiers such as *, +, and {} are greedy by default, meaning they match as much text as possible while still allowing the overall pattern to match. However, sometimes you may want to match as little text as possible. This is where lazy (or non-greedy) matching comes into play. Lazy quantifiers, denoted by appending a ? after the quantifier, match as little text as possible while still allowing the overall pattern to match.

### Boundaries
Boundaries help define where a match should start or end within the text. They do not match any characters themselves but rather represent positions within the text.

### Back-references
Back-references match the same text as previously matched by a capturing group. 

### Look-ahead and Look-behind
Look-ahead and look-behind assertions check for a match without including it in the result.

## Author
This tutorial was written by Joselyn. You can find more of my work at my GitHub [https://github.com/Josyyy24]