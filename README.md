# Regex Tutorial (Matching an Email)
In this tutorial you will learn to use regex for matching an email.
Regular expressions, or regex for short, are a universal series of special characters that define a search pattern.There are many cases in which they can be applied but in this tutorial we will focus on geting a general overview and matching an email.

## Summary

In this tutorial you will learn to use regex for matching an email.

## Table of Contents

- [Anchors](#anchors)
- [Quantifiers](#quantifiers)
- [Character Classes](#character-classes)
- [Grouping and Capturing](#grouping-and-capturing)
- [Bracket Expressions](#bracket-expressions)
- [Flags](#flags)
- [Back-references](#back-references)
- [Author](#author)

## Regex Components
A regex is considered a literal, so the pattern must be wrapped in slash characters (/).
We will analize the following regex:

^[\w-\.]+@([\w-]+\.)+[\w-]{2,4}$/g
## Anchors
The characters ^ and $ are the considered anchors.

  ^: Marks for the begining of the string. 
  $: Marks for the end of the string. 

If Multiline flag is enabled the anchor $ will mark the end of the line.
 (m): Multiline flag 
## Quantifiers

The quantifiers in our regex are  + , {}

+: Match one or more of the preceding object, in this case matching email name with email provider with .com. 

{2,4}:Match range between 2 and 4 of the preceding token, in this case the character set[\w-].

## Character Classes
The character classes are /w , .

\w: Matches any word character (alphanumeric & underscore)
This class is equivalent to the bracket expression [A-Za-z0-9_].

\.: Matches a "." character.

@: Matches a "@" character.

-: Matches a "-" character.

## Grouping and Capturing
Capturing group #1 : ([\w-]+\.) 
Groups multiple tokens together and creates a capture group for extracting a substring or using backreference.


## Bracket Expressions
Character set #1: [\w-\.]
Matches any character in the set, in this case the email name.

Character set #2: [\w-]
Matches any character in the set, in this case the email provider.

Character set #3: [\w-]
Matches any character in the set, in this case ".com" or else.

## Flags
g: Means Global search, Retain the index of the last match, allowing iterative searches 
## Back-references

-[https://www.youtube.com/watch?v=7DG3kCDx53c]
-[https://coding-boot-camp.github.io/full-stack/computer-science/regex-tutorial]
-[https://regexr.com/3e48o]

## Author
 ### Email
  dmxtechinn@gmail.com

  Issues or questions? Email me [here](mailto:dmxtechinn@gmail.com).

  ### github
  dmxtech

  
 See more work at my Github profile: [Github profile](https://github.com/dmxtech).
