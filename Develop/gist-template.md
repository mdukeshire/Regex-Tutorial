# Regex-Tutorial

 This tutorial will look at regular expressions (Regex), what they are and how they work.

## Summary

Regular expressions are patterns used to match character combinations in strings. In JavaScript, regular expressions are also objects. These patterns are used with the exec() and test() methods of RegExp, and with the match(), matchAll(), replace(), replaceAll(), search(), and split() methods of String. 

## Table of Contents

- [Anchors](#anchors)
- [Quantifiers](#quantifiers)
- [Bracket Expressions](#bracket-expressions)
- [Character Classes](#character-classes)

## Regex Components

### Anchors
Characters within the regex that allow the user to match strings that begins or ends with certain characters.

* `^` - matches any string that start with the anterior word
* `$` - matches a string that end with preceeding word before the character

### Quantifiers
Characters within the regex that specify how many instances a character, group, or class must be represented in the input to be matched.

* `*` - matches a string that has the anterior followed by zero or more of the last character
* `+` - matches a string that has the anterior followed by one or more of the last character
* `?` - matches a string that has the atnerior follwoed by zero or one of the last character
* `{}` -  matches a string that has the anterior followed by how ever many the number in the brackets of the last character in the string
* `()*` - matches a string that has any anterior characters followed by zero or more copies of the string within the brackets

### Bracket Expressions
Characters enclosed by a bracket `[]` matching any single character within the brackets. 

* `[]` - matching any single character within the brackets
* `[]%` - matching the string inside the brackets before the `%`
* `[^]` - matching any string that has not a letter from within the brackets (negation of expression)

### Character Classes
Tells the regex engine to match only one out serveral specific characters, such as digits, words, or whitespace.

* `\d` - matches a single character that is a digit
* `\w` - matches a word character (any alphanumeric character plus underscore)
* `\s` - matches a whitespace character (including tabs and line brakes)
* `.` - matches any character
* the capital case for any aformentioned characters will inverse the match

## Author
Matt Dukeshire
Email: MDukeshire07@gmail.com
GitHub: mdukeshire
GitHub Link: https://github.com/mdukeshire