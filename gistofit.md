# 
<div align = "center" id="top">
<img width = "500px" height="200px" src="assets/welcome.svg"/>
</div>



## 🎗 INTRODUCTORY SUMMARY:

- REGEX(Regular expression): Is a sequence of characters that defines a search pattern.

I started this assignment by researching "Which regex is used the most?", I came across this article

<https://digitalfortress.tech/tips/top-15-commonly-used-regex/> and I chose "Complex password strength" because

I feel I would use that the most in the real world. I always like to do things a little differently and I like to think

outside the box. Therefore, I have created a tutorial that explains how a specific regular expression, or regex, functions 

by breaking down each part of the expression and describing what it does. A Complex Password Strength: Should have 1

lowercase letter, 1 uppercase letter, 1 number, 1 special character and be at least 8 characters long.  

``
/(?=(.*[0-9]))(?=.*[\!@#$%^&*()\\[\]{}\-_+=~`|:;"'<>,./?])(?=.*[a-z])(?=(.*[A-Z]))(?=(.*)).{8,}/
``

## 🎗 TABLE OF CONTENTS:

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
- [ABOUT THE AUTHOR](#ABOUT-THE-AUTHOR)

## 🎗 REGEX COMPONENTS:

/(?=(.*[0-9]))(?=.*[\!@#$%^&*()\\[\]{}\-_+=~`|:;"'<>,./?])(?=.*[a-z])(?=(.*[A-Z]))(?=(.*)).{8,}/

### 🎗 Anchors:

- Open: Indicates the start of a regular expression.

      `start '/' end of the string`

- Close: Indicates the end of a regular expression.

### 🎗 Quantifiers:

- The {8,} which sets the length of the password minimum of 8 characters.

- There are five `.*` which is 0 or more, it is also called 'the wildcard' because it matches everything to preceding text.

- `.` Calls for any character.

### 🎗 OR Operator:

- The OR operator acts as a boolean using the | symbol by matching the expression before or after the | symbol.

### 🎗 Character Classes:

- The [A-Z] expression matches a character in the range from ‘A’ to ‘Z’ which is case sensitive.

- The expression [a-z] will match from range of ‘a’ to ‘z’, case sensitive.

- [0-9]

### 🎗 Flags:

- N/A

### 🎗 Grouping and Capturing:

- Groups are represented by '()', Groups can have multiple expressions to create a capture group. `(?=(.*[0-9]))`

### 🎗 Bracket Expressions:

- Bracket expressions are a list of characters enclosed by '[]' and will match any single character in that list.

- Bracket expressions are used in this example in combination with character classes.

``
[0-9], [\!@#$%^&*()\\[\], [a-z], [A-Z]
``

### 🎗 Greedy and Lazy Match:

- The ? makes the preceding quantifier lazy, causing it to match as few characters as possible.

- The .* is used to match anything.

- `.` Is used to match any character.



### 🎗 Boundaries:

- N/A

### 🎗 Back-references:

- `\\` Are used to escape special characters.

### 🎗 Look-ahead and Look-behind:

- There are five positive look-aheads. `?=` Look-aheads allow you to match groups before or 

after without including in your result.

## 🎗 ABOUT THE AUTHOR:

<a href="https://github.com/jonsno29" target="_blank"><img src="https://img.shields.io/badge/Github-jonsno29-red?style=for-the-badge&logo=github"></a>

📫 The best way to reach me over is Linkedin. You can also send me an e-mail to Snoverjon@gmail.com.

- My name is Jon Snover and I am a University Of Minnesota, Full-Stack Coding Bootcamp Student.

- <https://gist.github.com/JonSno29>

- <https://github.com/JonSno29/Gist-Of-PWStrength/blob/main/gistofit.md>


